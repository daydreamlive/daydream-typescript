# SDTurbo4LatentPreprocessingProcessor

## Example Usage

```typescript
import { SDTurbo4LatentPreprocessingProcessor } from "@daydreamlive/sdk/models";

let value: SDTurbo4LatentPreprocessingProcessor = {
  type: "latent_feedback",
};
```

## Fields

| Field                                                                                  | Type                                                                                   | Required                                                                               | Description                                                                            |
| -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| `type`                                                                                 | [models.SDTurbo4LatentPreprocessingType](../models/sdturbo4latentpreprocessingtype.md) | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `enabled`                                                                              | *boolean*                                                                              | :heavy_minus_sign:                                                                     | Whether this processor is active                                                       |
| `params`                                                                               | Record<string, *any*>                                                                  | :heavy_minus_sign:                                                                     | N/A                                                                                    |