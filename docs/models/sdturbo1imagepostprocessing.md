# SDTurbo1ImagePostprocessing

List of image postprocessor configurations for image processing
      ⚠️ NOTE: realesrgan_trt processor requires a restart to change because it affects resolution.
      

## Example Usage

```typescript
import { SDTurbo1ImagePostprocessing } from "daydream-sdk/models";

let value: SDTurbo1ImagePostprocessing = {
  processors: [
    {
      type: "upscale",
    },
  ],
};
```

## Fields

| Field                                                                                              | Type                                                                                               | Required                                                                                           | Description                                                                                        |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| `enabled`                                                                                          | *boolean*                                                                                          | :heavy_minus_sign:                                                                                 | Whether this processor config is active                                                            |
| `processors`                                                                                       | [models.SDTurbo1ImagePostprocessingProcessor](../models/sdturbo1imagepostprocessingprocessor.md)[] | :heavy_check_mark:                                                                                 | List of image processors to apply                                                                  |