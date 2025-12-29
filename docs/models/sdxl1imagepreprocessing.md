# Sdxl1ImagePreprocessing

List of image preprocessor configurations for image processing

## Example Usage

```typescript
import { Sdxl1ImagePreprocessing } from "@daydreamlive/sdk/models";

let value: Sdxl1ImagePreprocessing = {
  processors: [
    {
      type: "realesrgan_trt",
    },
  ],
};
```

## Fields

| Field                                                                                      | Type                                                                                       | Required                                                                                   | Description                                                                                |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| `enabled`                                                                                  | *boolean*                                                                                  | :heavy_minus_sign:                                                                         | Whether this processor config is active                                                    |
| `processors`                                                                               | [models.Sdxl1ImagePreprocessingProcessor](../models/sdxl1imagepreprocessingprocessor.md)[] | :heavy_check_mark:                                                                         | List of image processors to apply                                                          |