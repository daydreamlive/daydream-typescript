# Sdxl2ImagePreprocessing

List of image preprocessor configurations for image processing

## Example Usage

```typescript
import { Sdxl2ImagePreprocessing } from "@daydreamlive/sdk/models";

let value: Sdxl2ImagePreprocessing = {
  processors: [],
};
```

## Fields

| Field                                                                                      | Type                                                                                       | Required                                                                                   | Description                                                                                |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| `enabled`                                                                                  | *boolean*                                                                                  | :heavy_minus_sign:                                                                         | Whether this processor config is active                                                    |
| `processors`                                                                               | [models.Sdxl2ImagePreprocessingProcessor](../models/sdxl2imagepreprocessingprocessor.md)[] | :heavy_check_mark:                                                                         | List of image processors to apply                                                          |