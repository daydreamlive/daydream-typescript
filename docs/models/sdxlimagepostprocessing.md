# SDXLImagePostprocessing

List of image postprocessor configurations for image processing
      ⚠️ NOTE: realesrgan_trt processor requires a restart to change because it affects resolution.
      

## Example Usage

```typescript
import { SDXLImagePostprocessing } from "@daydreamlive/sdk/models";

let value: SDXLImagePostprocessing = {
  processors: [
    {
      type: "depth",
    },
  ],
};
```

## Fields

| Field                                                                                      | Type                                                                                       | Required                                                                                   | Description                                                                                |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| `enabled`                                                                                  | *boolean*                                                                                  | :heavy_minus_sign:                                                                         | Whether this processor config is active                                                    |
| `processors`                                                                               | [models.SDXLImagePostprocessingProcessor](../models/sdxlimagepostprocessingprocessor.md)[] | :heavy_check_mark:                                                                         | List of image processors to apply                                                          |