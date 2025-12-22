# SDTurbo2LatentPreprocessingProcessor

## Example Usage

```typescript
import { SDTurbo2LatentPreprocessingProcessor } from "daydream-sdk/models";

let value: SDTurbo2LatentPreprocessingProcessor = {
  type: "latent_feedback",
};
```

## Fields

| Field                                                                                  | Type                                                                                   | Required                                                                               | Description                                                                            |
| -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| `type`                                                                                 | [models.SDTurbo2LatentPreprocessingType](../models/sdturbo2latentpreprocessingtype.md) | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `enabled`                                                                              | *boolean*                                                                              | :heavy_minus_sign:                                                                     | Whether this processor is active                                                       |
| `params`                                                                               | Record<string, *any*>                                                                  | :heavy_minus_sign:                                                                     | N/A                                                                                    |