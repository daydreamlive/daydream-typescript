# SDTurbo1LatentPreprocessingProcessor

## Example Usage

```typescript
import { SDTurbo1LatentPreprocessingProcessor } from "daydream-sdk/models";

let value: SDTurbo1LatentPreprocessingProcessor = {
  type: "latent_feedback",
};
```

## Fields

| Field                                                                                  | Type                                                                                   | Required                                                                               | Description                                                                            |
| -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| `type`                                                                                 | [models.SDTurbo1LatentPreprocessingType](../models/sdturbo1latentpreprocessingtype.md) | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `enabled`                                                                              | *boolean*                                                                              | :heavy_minus_sign:                                                                     | Whether this processor is active                                                       |
| `params`                                                                               | Record<string, *any*>                                                                  | :heavy_minus_sign:                                                                     | N/A                                                                                    |