# UpdateStreamRequest

## Example Usage

```typescript
import { UpdateStreamRequest } from "@daydreamlive/sdk/models/operations";

let value: UpdateStreamRequest = {
  id: "<id>",
  body: {
    pipeline: "streamdiffusion",
    params: {
      modelId: "stabilityai/sd-turbo",
    },
  },
};
```

## Fields

| Field                                | Type                                 | Required                             | Description                          |
| ------------------------------------ | ------------------------------------ | ------------------------------------ | ------------------------------------ |
| `id`                                 | *string*                             | :heavy_check_mark:                   | ID of the stream to update           |
| `body`                               | *operations.UpdateStreamRequestBody* | :heavy_check_mark:                   | N/A                                  |