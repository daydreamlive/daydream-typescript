# SDTurbo3LatentPreprocessingProcessor

## Example Usage

```typescript
import { SDTurbo3LatentPreprocessingProcessor } from "@daydreamlive/sdk/models";

let value: SDTurbo3LatentPreprocessingProcessor = {
  type: "latent_feedback",
};
```

## Fields

| Field                                                                                  | Type                                                                                   | Required                                                                               | Description                                                                            |
| -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| `type`                                                                                 | [models.SDTurbo3LatentPreprocessingType](../models/sdturbo3latentpreprocessingtype.md) | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `enabled`                                                                              | *boolean*                                                                              | :heavy_minus_sign:                                                                     | Whether this processor is active                                                       |
| `params`                                                                               | Record<string, *any*>                                                                  | :heavy_minus_sign:                                                                     | N/A                                                                                    |