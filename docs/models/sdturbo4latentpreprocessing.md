# SDTurbo4LatentPreprocessing

List of latent preprocessor configurations for latent processing

## Example Usage

```typescript
import { SDTurbo4LatentPreprocessing } from "@daydreamlive/sdk/models";

let value: SDTurbo4LatentPreprocessing = {
  processors: [],
};
```

## Fields

| Field                                                                                              | Type                                                                                               | Required                                                                                           | Description                                                                                        |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| `enabled`                                                                                          | *boolean*                                                                                          | :heavy_minus_sign:                                                                                 | Whether this processor config is active                                                            |
| `processors`                                                                                       | [models.SDTurbo4LatentPreprocessingProcessor](../models/sdturbo4latentpreprocessingprocessor.md)[] | :heavy_check_mark:                                                                                 | List of latent processors to apply                                                                 |