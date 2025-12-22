# Sd15LatentPreprocessing

List of latent preprocessor configurations for latent processing

## Example Usage

```typescript
import { Sd15LatentPreprocessing } from "daydream-sdk/models";

let value: Sd15LatentPreprocessing = {
  processors: [
    {
      type: "latent_feedback",
    },
  ],
};
```

## Fields

| Field                                                                                      | Type                                                                                       | Required                                                                                   | Description                                                                                |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| `enabled`                                                                                  | *boolean*                                                                                  | :heavy_minus_sign:                                                                         | Whether this processor config is active                                                    |
| `processors`                                                                               | [models.Sd15LatentPreprocessingProcessor](../models/sd15latentpreprocessingprocessor.md)[] | :heavy_check_mark:                                                                         | List of latent processors to apply                                                         |