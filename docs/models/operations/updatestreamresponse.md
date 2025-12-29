# UpdateStreamResponse

Default Response

## Example Usage

```typescript
import { UpdateStreamResponse } from "@daydreamlive/sdk/models/operations";

let value: UpdateStreamResponse = {
  pipeline: "streamdiffusion",
  params: {
    modelId: "stabilityai/sdxl-turbo",
  },
  id: "<id>",
  streamKey: "<value>",
  createdAt: "1713619354714",
  outputPlaybackId: "<id>",
  name: "<value>",
  author: "<value>",
  fromPlayground: true,
  gatewayHost: "<value>",
  isSmokeTest: false,
  whipUrl: "https://tepid-newsstand.biz/",
};
```

## Fields

| Field                                                                                              | Type                                                                                               | Required                                                                                           | Description                                                                                        |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| `pipeline`                                                                                         | [operations.UpdateStreamPipelineResponse](../../models/operations/updatestreampipelineresponse.md) | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `params`                                                                                           | *operations.UpdateStreamParamsResponse*                                                            | :heavy_check_mark:                                                                                 | N/A                                                                                                |
| `id`                                                                                               | *string*                                                                                           | :heavy_check_mark:                                                                                 | Unique identifier for the stream                                                                   |
| `streamKey`                                                                                        | *string*                                                                                           | :heavy_check_mark:                                                                                 | Unique key used for streaming to this endpoint                                                     |
| `outputStreamUrl`                                                                                  | *string*                                                                                           | :heavy_minus_sign:                                                                                 | URL where the processed stream output can be accessed                                              |
| `createdAt`                                                                                        | *string*                                                                                           | :heavy_check_mark:                                                                                 | ISO timestamp when the stream was created                                                          |
| `outputPlaybackId`                                                                                 | *string*                                                                                           | :heavy_check_mark:                                                                                 | Playback ID for accessing the stream output                                                        |
| `name`                                                                                             | *string*                                                                                           | :heavy_check_mark:                                                                                 | Human-readable name of the stream                                                                  |
| `author`                                                                                           | *string*                                                                                           | :heavy_check_mark:                                                                                 | ID of the user who created this stream                                                             |
| `fromPlayground`                                                                                   | *boolean*                                                                                          | :heavy_check_mark:                                                                                 | Whether this stream was created from the playground interface                                      |
| `gatewayHost`                                                                                      | *string*                                                                                           | :heavy_check_mark:                                                                                 | Gateway server hostname handling this stream                                                       |
| `isSmokeTest`                                                                                      | *boolean*                                                                                          | :heavy_check_mark:                                                                                 | Whether this is a smoke test stream                                                                |
| `whipUrl`                                                                                          | *string*                                                                                           | :heavy_check_mark:                                                                                 | WebRTC WHIP URL for stream ingestion                                                               |