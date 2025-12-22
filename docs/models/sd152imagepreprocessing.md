# Sd152ImagePreprocessing

List of image preprocessor configurations for image processing

## Example Usage

```typescript
import { Sd152ImagePreprocessing } from "daydream-sdk/models";

let value: Sd152ImagePreprocessing = {
  processors: [],
};
```

## Fields

| Field                                                                                      | Type                                                                                       | Required                                                                                   | Description                                                                                |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| `enabled`                                                                                  | *boolean*                                                                                  | :heavy_minus_sign:                                                                         | Whether this processor config is active                                                    |
| `processors`                                                                               | [models.Sd152ImagePreprocessingProcessor](../models/sd152imagepreprocessingprocessor.md)[] | :heavy_check_mark:                                                                         | List of image processors to apply                                                          |