# SDXLLatentPreprocessing

List of latent preprocessor configurations for latent processing

## Example Usage

```typescript
import { SDXLLatentPreprocessing } from "daydream-sdk/models";

let value: SDXLLatentPreprocessing = {
  processors: [],
};
```

## Fields

| Field                                                                                      | Type                                                                                       | Required                                                                                   | Description                                                                                |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| `enabled`                                                                                  | *boolean*                                                                                  | :heavy_minus_sign:                                                                         | Whether this processor config is active                                                    |
| `processors`                                                                               | [models.SDXLLatentPreprocessingProcessor](../models/sdxllatentpreprocessingprocessor.md)[] | :heavy_check_mark:                                                                         | List of latent processors to apply                                                         |