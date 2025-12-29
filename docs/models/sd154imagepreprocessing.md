# Sd154ImagePreprocessing

List of image preprocessor configurations for image processing

## Example Usage

```typescript
import { Sd154ImagePreprocessing } from "@daydreamlive/sdk/models";

let value: Sd154ImagePreprocessing = {
  processors: [],
};
```

## Fields

| Field                                                                                      | Type                                                                                       | Required                                                                                   | Description                                                                                |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| `enabled`                                                                                  | *boolean*                                                                                  | :heavy_minus_sign:                                                                         | Whether this processor config is active                                                    |
| `processors`                                                                               | [models.Sd154ImagePreprocessingProcessor](../models/sd154imagepreprocessingprocessor.md)[] | :heavy_check_mark:                                                                         | List of image processors to apply                                                          |