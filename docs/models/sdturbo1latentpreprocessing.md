# SDTurbo1LatentPreprocessing

List of latent preprocessor configurations for latent processing

## Example Usage

```typescript
import { SDTurbo1LatentPreprocessing } from "@daydreamlive/sdk/models";

let value: SDTurbo1LatentPreprocessing = {
  processors: [
    {
      type: "latent_feedback",
    },
  ],
};
```

## Fields

| Field                                                                                              | Type                                                                                               | Required                                                                                           | Description                                                                                        |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| `enabled`                                                                                          | *boolean*                                                                                          | :heavy_minus_sign:                                                                                 | Whether this processor config is active                                                            |
| `processors`                                                                                       | [models.SDTurbo1LatentPreprocessingProcessor](../models/sdturbo1latentpreprocessingprocessor.md)[] | :heavy_check_mark:                                                                                 | List of latent processors to apply                                                                 |