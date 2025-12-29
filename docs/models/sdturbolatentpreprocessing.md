# SDTurboLatentPreprocessing

List of latent preprocessor configurations for latent processing

## Example Usage

```typescript
import { SDTurboLatentPreprocessing } from "@daydreamlive/sdk/models";

let value: SDTurboLatentPreprocessing = {
  processors: [],
};
```

## Fields

| Field                                                                                            | Type                                                                                             | Required                                                                                         | Description                                                                                      |
| ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| `enabled`                                                                                        | *boolean*                                                                                        | :heavy_minus_sign:                                                                               | Whether this processor config is active                                                          |
| `processors`                                                                                     | [models.SDTurboLatentPreprocessingProcessor](../models/sdturbolatentpreprocessingprocessor.md)[] | :heavy_check_mark:                                                                               | List of latent processors to apply                                                               |