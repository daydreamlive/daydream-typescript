# SDTurbo2LatentPreprocessing

List of latent preprocessor configurations for latent processing

## Example Usage

```typescript
import { SDTurbo2LatentPreprocessing } from "@daydreamlive/sdk/models";

let value: SDTurbo2LatentPreprocessing = {
  processors: [],
};
```

## Fields

| Field                                                                                              | Type                                                                                               | Required                                                                                           | Description                                                                                        |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| `enabled`                                                                                          | *boolean*                                                                                          | :heavy_minus_sign:                                                                                 | Whether this processor config is active                                                            |
| `processors`                                                                                       | [models.SDTurbo2LatentPreprocessingProcessor](../models/sdturbo2latentpreprocessingprocessor.md)[] | :heavy_check_mark:                                                                                 | List of latent processors to apply                                                                 |