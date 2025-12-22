# SDTurbo4ImagePostprocessing

List of image postprocessor configurations for image processing
      ⚠️ NOTE: realesrgan_trt processor requires a restart to change because it affects resolution.
      

## Example Usage

```typescript
import { SDTurbo4ImagePostprocessing } from "daydream-sdk/models";

let value: SDTurbo4ImagePostprocessing = {
  processors: [
    {
      type: "temporal_net_tensorrt",
    },
  ],
};
```

## Fields

| Field                                                                                              | Type                                                                                               | Required                                                                                           | Description                                                                                        |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| `enabled`                                                                                          | *boolean*                                                                                          | :heavy_minus_sign:                                                                                 | Whether this processor config is active                                                            |
| `processors`                                                                                       | [models.SDTurbo4ImagePostprocessingProcessor](../models/sdturbo4imagepostprocessingprocessor.md)[] | :heavy_check_mark:                                                                                 | List of image processors to apply                                                                  |