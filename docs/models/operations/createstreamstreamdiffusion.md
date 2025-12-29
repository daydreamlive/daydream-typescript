# CreateStreamStreamDiffusion

## Example Usage

```typescript
import { CreateStreamStreamDiffusion } from "@daydreamlive/sdk/models/operations";

let value: CreateStreamStreamDiffusion = {
  pipeline: "streamdiffusion",
  params: {
    modelId: "Lykon/dreamshaper-8",
  },
};
```

## Fields

| Field                                                                                            | Type                                                                                             | Required                                                                                         | Description                                                                                      |
| ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| `pipeline`                                                                                       | [operations.CreateStreamPipelineRequest](../../models/operations/createstreampipelinerequest.md) | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `params`                                                                                         | *operations.CreateStreamParamsRequest*                                                           | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `name`                                                                                           | *string*                                                                                         | :heavy_minus_sign:                                                                               | Human-readable name for the stream                                                               |
| `outputRtmpUrl`                                                                                  | *string*                                                                                         | :heavy_minus_sign:                                                                               | Custom RTMP URL for stream output destination                                                    |