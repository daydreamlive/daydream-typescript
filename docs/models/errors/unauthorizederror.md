# UnauthorizedError

Default Response

## Example Usage

```typescript
import { UnauthorizedError } from "@daydreamlive/sdk/models/errors";

// No examples available for this model
```

## Fields

| Field                                                       | Type                                                        | Required                                                    | Description                                                 |
| ----------------------------------------------------------- | ----------------------------------------------------------- | ----------------------------------------------------------- | ----------------------------------------------------------- |
| `success`                                                   | *boolean*                                                   | :heavy_minus_sign:                                          | Always false for error responses                            |
| `error`                                                     | *string*                                                    | :heavy_check_mark:                                          | User-facing error message                                   |
| `code`                                                      | *string*                                                    | :heavy_check_mark:                                          | Stable machine-readable error code, e.g., STREAMS/NOT_FOUND |
| `status`                                                    | *number*                                                    | :heavy_check_mark:                                          | HTTP status code                                            |
| `details`                                                   | *any*                                                       | :heavy_minus_sign:                                          | Optional structured details about the error                 |
| `requestId`                                                 | *string*                                                    | :heavy_minus_sign:                                          | Request identifier for correlation                          |
| `traceId`                                                   | *string*                                                    | :heavy_minus_sign:                                          | OpenTelemetry trace id for correlation                      |