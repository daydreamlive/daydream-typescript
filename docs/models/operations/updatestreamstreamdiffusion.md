# UpdateStreamStreamDiffusion

## Example Usage

```typescript
import { UpdateStreamStreamDiffusion } from "daydream-sdk/models/operations";

let value: UpdateStreamStreamDiffusion = {
  pipeline: "streamdiffusion",
  params: {
    modelId: "stabilityai/sdxl-turbo",
  },
};
```

## Fields

| Field                                                                                            | Type                                                                                             | Required                                                                                         | Description                                                                                      |
| ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| `pipeline`                                                                                       | [operations.UpdateStreamPipelineRequest](../../models/operations/updatestreampipelinerequest.md) | :heavy_check_mark:                                                                               | N/A                                                                                              |
| `params`                                                                                         | *operations.UpdateStreamParamsRequest*                                                           | :heavy_check_mark:                                                                               | N/A                                                                                              |