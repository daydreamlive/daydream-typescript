# SDTurbo3LatentPreprocessing

List of latent preprocessor configurations for latent processing

## Example Usage

```typescript
import { SDTurbo3LatentPreprocessing } from "@daydreamlive/sdk/models";

let value: SDTurbo3LatentPreprocessing = {
  processors: [],
};
```

## Fields

| Field                                                                                              | Type                                                                                               | Required                                                                                           | Description                                                                                        |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| `enabled`                                                                                          | *boolean*                                                                                          | :heavy_minus_sign:                                                                                 | Whether this processor config is active                                                            |
| `processors`                                                                                       | [models.SDTurbo3LatentPreprocessingProcessor](../models/sdturbo3latentpreprocessingprocessor.md)[] | :heavy_check_mark:                                                                                 | List of latent processors to apply                                                                 |