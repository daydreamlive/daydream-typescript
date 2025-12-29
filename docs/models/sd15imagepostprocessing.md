# Sd15ImagePostprocessing

List of image postprocessor configurations for image processing
      ⚠️ NOTE: realesrgan_trt processor requires a restart to change because it affects resolution.
      

## Example Usage

```typescript
import { Sd15ImagePostprocessing } from "@daydreamlive/sdk/models";

let value: Sd15ImagePostprocessing = {
  processors: [],
};
```

## Fields

| Field                                                                                      | Type                                                                                       | Required                                                                                   | Description                                                                                |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| `enabled`                                                                                  | *boolean*                                                                                  | :heavy_minus_sign:                                                                         | Whether this processor config is active                                                    |
| `processors`                                                                               | [models.Sd15ImagePostprocessingProcessor](../models/sd15imagepostprocessingprocessor.md)[] | :heavy_check_mark:                                                                         | List of image processors to apply                                                          |