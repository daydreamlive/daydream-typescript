# Public

## Overview

### Available Operations

* [create](#create) - Create a new stream
* [getAll](#getall) - Get all streams for user
* [delete](#delete) - Delete a stream
* [update](#update) - Update a stream
* [getById](#getbyid) - Get stream by ID

## create

Creates a new video processing stream with the specified configuration

### Example Usage

<!-- UsageSnippet language="typescript" operationID="createStream" method="post" path="/v1/streams" -->
```typescript
import { Daydream } from "daydream-sdk";

const daydream = new Daydream({
  bearer: process.env["DAYDREAM_BEARER"] ?? "",
});

async function run() {
  const result = await daydream.public.create({
    pipeline: "streamdiffusion",
    params: {
      modelId: "stabilityai/sdxl-turbo",
    },
  });

  console.log(result);
}

run();
```

### Standalone function

The standalone function version of this method:

```typescript
import { DaydreamCore } from "daydream-sdk/core.js";
import { streamsCreate } from "daydream-sdk/funcs/streamsCreate.js";

// Use `DaydreamCore` for best tree-shaking performance.
// You can create one instance of it to use across an application.
const daydream = new DaydreamCore({
  bearer: process.env["DAYDREAM_BEARER"] ?? "",
});

async function run() {
  const res = await streamsCreate(daydream, {
    pipeline: "streamdiffusion",
    params: {
      modelId: "stabilityai/sdxl-turbo",
    },
  });
  if (res.ok) {
    const { value: result } = res;
    console.log(result);
  } else {
    console.log("streamsCreate failed:", res.error);
  }
}

run();
```

### Parameters

| Parameter                                                                                                                                                                      | Type                                                                                                                                                                           | Required                                                                                                                                                                       | Description                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `request`                                                                                                                                                                      | [operations.CreateStreamRequest](../../models/operations/createstreamrequest.md)                                                                                               | :heavy_check_mark:                                                                                                                                                             | The request object to use for the request.                                                                                                                                     |
| `options`                                                                                                                                                                      | RequestOptions                                                                                                                                                                 | :heavy_minus_sign:                                                                                                                                                             | Used to set various options for making HTTP requests.                                                                                                                          |
| `options.fetchOptions`                                                                                                                                                         | [RequestInit](https://developer.mozilla.org/en-US/docs/Web/API/Request/Request#options)                                                                                        | :heavy_minus_sign:                                                                                                                                                             | Options that are passed to the underlying HTTP request. This can be used to inject extra headers for examples. All `Request` options, except `method` and `body`, are allowed. |
| `options.retries`                                                                                                                                                              | [RetryConfig](../../lib/utils/retryconfig.md)                                                                                                                                  | :heavy_minus_sign:                                                                                                                                                             | Enables retrying HTTP requests under certain failure conditions.                                                                                                               |

### Response

**Promise\<[operations.CreateStreamResponse](../../models/operations/createstreamresponse.md)\>**

### Errors

| Error Type                  | Status Code                 | Content Type                |
| --------------------------- | --------------------------- | --------------------------- |
| errors.BadRequestError      | 400                         | application/json            |
| errors.UnauthorizedError    | 401                         | application/json            |
| errors.ForbiddenError       | 403                         | application/json            |
| errors.NotFoundError        | 404                         | application/json            |
| errors.ConflictError        | 409                         | application/json            |
| errors.TooManyRequestsError | 429                         | application/json            |
| errors.InternalServerError  | 500                         | application/json            |
| errors.DaydreamDefaultError | 4XX, 5XX                    | \*/\*                       |

## getAll

Retrieves all streams belonging to the authenticated user

### Example Usage

<!-- UsageSnippet language="typescript" operationID="getAllStreams" method="get" path="/v1/streams" -->
```typescript
import { Daydream } from "daydream-sdk";

const daydream = new Daydream({
  bearer: process.env["DAYDREAM_BEARER"] ?? "",
});

async function run() {
  const result = await daydream.public.getAll();

  console.log(result);
}

run();
```

### Standalone function

The standalone function version of this method:

```typescript
import { DaydreamCore } from "daydream-sdk/core.js";
import { streamsGetAll } from "daydream-sdk/funcs/streamsGetAll.js";

// Use `DaydreamCore` for best tree-shaking performance.
// You can create one instance of it to use across an application.
const daydream = new DaydreamCore({
  bearer: process.env["DAYDREAM_BEARER"] ?? "",
});

async function run() {
  const res = await streamsGetAll(daydream);
  if (res.ok) {
    const { value: result } = res;
    console.log(result);
  } else {
    console.log("streamsGetAll failed:", res.error);
  }
}

run();
```

### Parameters

| Parameter                                                                                                                                                                      | Type                                                                                                                                                                           | Required                                                                                                                                                                       | Description                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `request`                                                                                                                                                                      | [operations.GetAllStreamsRequest](../../models/operations/getallstreamsrequest.md)                                                                                             | :heavy_check_mark:                                                                                                                                                             | The request object to use for the request.                                                                                                                                     |
| `options`                                                                                                                                                                      | RequestOptions                                                                                                                                                                 | :heavy_minus_sign:                                                                                                                                                             | Used to set various options for making HTTP requests.                                                                                                                          |
| `options.fetchOptions`                                                                                                                                                         | [RequestInit](https://developer.mozilla.org/en-US/docs/Web/API/Request/Request#options)                                                                                        | :heavy_minus_sign:                                                                                                                                                             | Options that are passed to the underlying HTTP request. This can be used to inject extra headers for examples. All `Request` options, except `method` and `body`, are allowed. |
| `options.retries`                                                                                                                                                              | [RetryConfig](../../lib/utils/retryconfig.md)                                                                                                                                  | :heavy_minus_sign:                                                                                                                                                             | Enables retrying HTTP requests under certain failure conditions.                                                                                                               |

### Response

**Promise\<[operations.GetAllStreamsResponse](../../models/operations/getallstreamsresponse.md)\>**

### Errors

| Error Type                  | Status Code                 | Content Type                |
| --------------------------- | --------------------------- | --------------------------- |
| errors.BadRequestError      | 400                         | application/json            |
| errors.UnauthorizedError    | 401                         | application/json            |
| errors.ForbiddenError       | 403                         | application/json            |
| errors.NotFoundError        | 404                         | application/json            |
| errors.ConflictError        | 409                         | application/json            |
| errors.TooManyRequestsError | 429                         | application/json            |
| errors.InternalServerError  | 500                         | application/json            |
| errors.DaydreamDefaultError | 4XX, 5XX                    | \*/\*                       |

## delete

Deletes a specific stream by ID for the authenticated user

### Example Usage

<!-- UsageSnippet language="typescript" operationID="deleteStream" method="delete" path="/v1/streams" -->
```typescript
import { Daydream } from "daydream-sdk";

const daydream = new Daydream({
  bearer: process.env["DAYDREAM_BEARER"] ?? "",
});

async function run() {
  const result = await daydream.public.delete({
    id: "<id>",
  });

  console.log(result);
}

run();
```

### Standalone function

The standalone function version of this method:

```typescript
import { DaydreamCore } from "daydream-sdk/core.js";
import { streamsDelete } from "daydream-sdk/funcs/streamsDelete.js";

// Use `DaydreamCore` for best tree-shaking performance.
// You can create one instance of it to use across an application.
const daydream = new DaydreamCore({
  bearer: process.env["DAYDREAM_BEARER"] ?? "",
});

async function run() {
  const res = await streamsDelete(daydream, {
    id: "<id>",
  });
  if (res.ok) {
    const { value: result } = res;
    console.log(result);
  } else {
    console.log("streamsDelete failed:", res.error);
  }
}

run();
```

### Parameters

| Parameter                                                                                                                                                                      | Type                                                                                                                                                                           | Required                                                                                                                                                                       | Description                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `request`                                                                                                                                                                      | [operations.DeleteStreamRequest](../../models/operations/deletestreamrequest.md)                                                                                               | :heavy_check_mark:                                                                                                                                                             | The request object to use for the request.                                                                                                                                     |
| `options`                                                                                                                                                                      | RequestOptions                                                                                                                                                                 | :heavy_minus_sign:                                                                                                                                                             | Used to set various options for making HTTP requests.                                                                                                                          |
| `options.fetchOptions`                                                                                                                                                         | [RequestInit](https://developer.mozilla.org/en-US/docs/Web/API/Request/Request#options)                                                                                        | :heavy_minus_sign:                                                                                                                                                             | Options that are passed to the underlying HTTP request. This can be used to inject extra headers for examples. All `Request` options, except `method` and `body`, are allowed. |
| `options.retries`                                                                                                                                                              | [RetryConfig](../../lib/utils/retryconfig.md)                                                                                                                                  | :heavy_minus_sign:                                                                                                                                                             | Enables retrying HTTP requests under certain failure conditions.                                                                                                               |

### Response

**Promise\<[operations.DeleteStreamResponse](../../models/operations/deletestreamresponse.md)\>**

### Errors

| Error Type                  | Status Code                 | Content Type                |
| --------------------------- | --------------------------- | --------------------------- |
| errors.BadRequestError      | 400                         | application/json            |
| errors.UnauthorizedError    | 401                         | application/json            |
| errors.ForbiddenError       | 403                         | application/json            |
| errors.NotFoundError        | 404                         | application/json            |
| errors.ConflictError        | 409                         | application/json            |
| errors.TooManyRequestsError | 429                         | application/json            |
| errors.InternalServerError  | 500                         | application/json            |
| errors.DaydreamDefaultError | 4XX, 5XX                    | \*/\*                       |

## update

Updates pipeline parameters for a specific stream by ID for the authenticated user

### Example Usage

<!-- UsageSnippet language="typescript" operationID="updateStream" method="patch" path="/v1/streams/{id}" -->
```typescript
import { Daydream } from "daydream-sdk";

const daydream = new Daydream({
  bearer: process.env["DAYDREAM_BEARER"] ?? "",
});

async function run() {
  const result = await daydream.public.update({
    id: "<id>",
    body: {
      pipeline: "streamdiffusion",
      params: {
        modelId: "Lykon/dreamshaper-8",
      },
    },
  });

  console.log(result);
}

run();
```

### Standalone function

The standalone function version of this method:

```typescript
import { DaydreamCore } from "daydream-sdk/core.js";
import { streamsUpdate } from "daydream-sdk/funcs/streamsUpdate.js";

// Use `DaydreamCore` for best tree-shaking performance.
// You can create one instance of it to use across an application.
const daydream = new DaydreamCore({
  bearer: process.env["DAYDREAM_BEARER"] ?? "",
});

async function run() {
  const res = await streamsUpdate(daydream, {
    id: "<id>",
    body: {
      pipeline: "streamdiffusion",
      params: {
        modelId: "Lykon/dreamshaper-8",
      },
    },
  });
  if (res.ok) {
    const { value: result } = res;
    console.log(result);
  } else {
    console.log("streamsUpdate failed:", res.error);
  }
}

run();
```

### Parameters

| Parameter                                                                                                                                                                      | Type                                                                                                                                                                           | Required                                                                                                                                                                       | Description                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `request`                                                                                                                                                                      | [operations.UpdateStreamRequest](../../models/operations/updatestreamrequest.md)                                                                                               | :heavy_check_mark:                                                                                                                                                             | The request object to use for the request.                                                                                                                                     |
| `options`                                                                                                                                                                      | RequestOptions                                                                                                                                                                 | :heavy_minus_sign:                                                                                                                                                             | Used to set various options for making HTTP requests.                                                                                                                          |
| `options.fetchOptions`                                                                                                                                                         | [RequestInit](https://developer.mozilla.org/en-US/docs/Web/API/Request/Request#options)                                                                                        | :heavy_minus_sign:                                                                                                                                                             | Options that are passed to the underlying HTTP request. This can be used to inject extra headers for examples. All `Request` options, except `method` and `body`, are allowed. |
| `options.retries`                                                                                                                                                              | [RetryConfig](../../lib/utils/retryconfig.md)                                                                                                                                  | :heavy_minus_sign:                                                                                                                                                             | Enables retrying HTTP requests under certain failure conditions.                                                                                                               |

### Response

**Promise\<[operations.UpdateStreamResponse](../../models/operations/updatestreamresponse.md)\>**

### Errors

| Error Type                  | Status Code                 | Content Type                |
| --------------------------- | --------------------------- | --------------------------- |
| errors.BadRequestError      | 400                         | application/json            |
| errors.UnauthorizedError    | 401                         | application/json            |
| errors.ForbiddenError       | 403                         | application/json            |
| errors.NotFoundError        | 404                         | application/json            |
| errors.ConflictError        | 409                         | application/json            |
| errors.TooManyRequestsError | 429                         | application/json            |
| errors.InternalServerError  | 500                         | application/json            |
| errors.DaydreamDefaultError | 4XX, 5XX                    | \*/\*                       |

## getById

Retrieves a specific stream by its ID. Users can only access their own streams unless they have admin privileges.

### Example Usage

<!-- UsageSnippet language="typescript" operationID="getStreamById" method="get" path="/v1/streams/{id}" -->
```typescript
import { Daydream } from "daydream-sdk";

const daydream = new Daydream({
  bearer: process.env["DAYDREAM_BEARER"] ?? "",
});

async function run() {
  const result = await daydream.public.getById({
    id: "<id>",
  });

  console.log(result);
}

run();
```

### Standalone function

The standalone function version of this method:

```typescript
import { DaydreamCore } from "daydream-sdk/core.js";
import { streamsGetById } from "daydream-sdk/funcs/streamsGetById.js";

// Use `DaydreamCore` for best tree-shaking performance.
// You can create one instance of it to use across an application.
const daydream = new DaydreamCore({
  bearer: process.env["DAYDREAM_BEARER"] ?? "",
});

async function run() {
  const res = await streamsGetById(daydream, {
    id: "<id>",
  });
  if (res.ok) {
    const { value: result } = res;
    console.log(result);
  } else {
    console.log("streamsGetById failed:", res.error);
  }
}

run();
```

### Parameters

| Parameter                                                                                                                                                                      | Type                                                                                                                                                                           | Required                                                                                                                                                                       | Description                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `request`                                                                                                                                                                      | [operations.GetStreamByIdRequest](../../models/operations/getstreambyidrequest.md)                                                                                             | :heavy_check_mark:                                                                                                                                                             | The request object to use for the request.                                                                                                                                     |
| `options`                                                                                                                                                                      | RequestOptions                                                                                                                                                                 | :heavy_minus_sign:                                                                                                                                                             | Used to set various options for making HTTP requests.                                                                                                                          |
| `options.fetchOptions`                                                                                                                                                         | [RequestInit](https://developer.mozilla.org/en-US/docs/Web/API/Request/Request#options)                                                                                        | :heavy_minus_sign:                                                                                                                                                             | Options that are passed to the underlying HTTP request. This can be used to inject extra headers for examples. All `Request` options, except `method` and `body`, are allowed. |
| `options.retries`                                                                                                                                                              | [RetryConfig](../../lib/utils/retryconfig.md)                                                                                                                                  | :heavy_minus_sign:                                                                                                                                                             | Enables retrying HTTP requests under certain failure conditions.                                                                                                               |

### Response

**Promise\<[operations.GetStreamByIdResponse](../../models/operations/getstreambyidresponse.md)\>**

### Errors

| Error Type                  | Status Code                 | Content Type                |
| --------------------------- | --------------------------- | --------------------------- |
| errors.BadRequestError      | 400                         | application/json            |
| errors.UnauthorizedError    | 401                         | application/json            |
| errors.ForbiddenError       | 403                         | application/json            |
| errors.NotFoundError        | 404                         | application/json            |
| errors.ConflictError        | 409                         | application/json            |
| errors.TooManyRequestsError | 429                         | application/json            |
| errors.InternalServerError  | 500                         | application/json            |
| errors.DaydreamDefaultError | 4XX, 5XX                    | \*/\*                       |