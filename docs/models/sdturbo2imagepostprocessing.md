# SDTurbo2ImagePostprocessing

List of image postprocessor configurations for image processing
      ⚠️ NOTE: realesrgan_trt processor requires a restart to change because it affects resolution.
      

## Example Usage

```typescript
import { SDTurbo2ImagePostprocessing } from "@daydreamlive/sdk/models";

let value: SDTurbo2ImagePostprocessing = {
  processors: [],
};
```

## Fields

| Field                                                                                              | Type                                                                                               | Required                                                                                           | Description                                                                                        |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| `enabled`                                                                                          | *boolean*                                                                                          | :heavy_minus_sign:                                                                                 | Whether this processor config is active                                                            |
| `processors`                                                                                       | [models.SDTurbo2ImagePostprocessingProcessor](../models/sdturbo2imagepostprocessingprocessor.md)[] | :heavy_check_mark:                                                                                 | List of image processors to apply                                                                  |