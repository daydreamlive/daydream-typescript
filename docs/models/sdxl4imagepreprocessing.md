# Sdxl4ImagePreprocessing

List of image preprocessor configurations for image processing

## Example Usage

```typescript
import { Sdxl4ImagePreprocessing } from "daydream-sdk/models";

let value: Sdxl4ImagePreprocessing = {
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
| `processors`                                                                               | [models.Sdxl4ImagePreprocessingProcessor](../models/sdxl4imagepreprocessingprocessor.md)[] | :heavy_check_mark:                                                                         | List of image processors to apply                                                          |