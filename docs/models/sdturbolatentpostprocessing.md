# SDTurboLatentPostprocessing

List of latent postprocessor configurations for latent processing

## Example Usage

```typescript
import { SDTurboLatentPostprocessing } from "daydream-sdk/models";

let value: SDTurboLatentPostprocessing = {
  processors: [],
};
```

## Fields

| Field                                                                                              | Type                                                                                               | Required                                                                                           | Description                                                                                        |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| `enabled`                                                                                          | *boolean*                                                                                          | :heavy_minus_sign:                                                                                 | Whether this processor config is active                                                            |
| `processors`                                                                                       | [models.SDTurboLatentPostprocessingProcessor](../models/sdturbolatentpostprocessingprocessor.md)[] | :heavy_check_mark:                                                                                 | List of latent processors to apply                                                                 |