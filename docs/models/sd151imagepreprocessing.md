# Sd151ImagePreprocessing

List of image preprocessor configurations for image processing

## Example Usage

```typescript
import { Sd151ImagePreprocessing } from "@daydreamlive/sdk/models";

let value: Sd151ImagePreprocessing = {
  processors: [],
};
```

## Fields

| Field                                                                                      | Type                                                                                       | Required                                                                                   | Description                                                                                |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| `enabled`                                                                                  | *boolean*                                                                                  | :heavy_minus_sign:                                                                         | Whether this processor config is active                                                    |
| `processors`                                                                               | [models.Sd151ImagePreprocessingProcessor](../models/sd151imagepreprocessingprocessor.md)[] | :heavy_check_mark:                                                                         | List of image processors to apply                                                          |