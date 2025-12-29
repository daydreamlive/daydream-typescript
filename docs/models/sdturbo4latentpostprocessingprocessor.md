# SDTurbo4LatentPostprocessingProcessor

## Example Usage

```typescript
import { SDTurbo4LatentPostprocessingProcessor } from "@daydreamlive/sdk/models";

let value: SDTurbo4LatentPostprocessingProcessor = {
  type: "latent_feedback",
};
```

## Fields

| Field                                                                                    | Type                                                                                     | Required                                                                                 | Description                                                                              |
| ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| `type`                                                                                   | [models.SDTurbo4LatentPostprocessingType](../models/sdturbo4latentpostprocessingtype.md) | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `enabled`                                                                                | *boolean*                                                                                | :heavy_minus_sign:                                                                       | Whether this processor is active                                                         |
| `params`                                                                                 | Record<string, *any*>                                                                    | :heavy_minus_sign:                                                                       | N/A                                                                                      |