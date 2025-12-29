# Sdxl3ImagePreprocessing

List of image preprocessor configurations for image processing

## Example Usage

```typescript
import { Sdxl3ImagePreprocessing } from "@daydreamlive/sdk/models";

let value: Sdxl3ImagePreprocessing = {
  processors: [
    {
      type: "openpose",
    },
  ],
};
```

## Fields

| Field                                                                                      | Type                                                                                       | Required                                                                                   | Description                                                                                |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| `enabled`                                                                                  | *boolean*                                                                                  | :heavy_minus_sign:                                                                         | Whether this processor config is active                                                    |
| `processors`                                                                               | [models.Sdxl3ImagePreprocessingProcessor](../models/sdxl3imagepreprocessingprocessor.md)[] | :heavy_check_mark:                                                                         | List of image processors to apply                                                          |