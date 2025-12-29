# SDTurbo2LatentPostprocessingProcessor

## Example Usage

```typescript
import { SDTurbo2LatentPostprocessingProcessor } from "@daydreamlive/sdk/models";

let value: SDTurbo2LatentPostprocessingProcessor = {
  type: "latent_feedback",
};
```

## Fields

| Field                                                                                    | Type                                                                                     | Required                                                                                 | Description                                                                              |
| ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| `type`                                                                                   | [models.SDTurbo2LatentPostprocessingType](../models/sdturbo2latentpostprocessingtype.md) | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `enabled`                                                                                | *boolean*                                                                                | :heavy_minus_sign:                                                                       | Whether this processor is active                                                         |
| `params`                                                                                 | Record<string, *any*>                                                                    | :heavy_minus_sign:                                                                       | N/A                                                                                      |