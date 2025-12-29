# SDTurbo3LatentPostprocessingProcessor

## Example Usage

```typescript
import { SDTurbo3LatentPostprocessingProcessor } from "@daydreamlive/sdk/models";

let value: SDTurbo3LatentPostprocessingProcessor = {
  type: "latent_feedback",
};
```

## Fields

| Field                                                                                    | Type                                                                                     | Required                                                                                 | Description                                                                              |
| ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| `type`                                                                                   | [models.SDTurbo3LatentPostprocessingType](../models/sdturbo3latentpostprocessingtype.md) | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `enabled`                                                                                | *boolean*                                                                                | :heavy_minus_sign:                                                                       | Whether this processor is active                                                         |
| `params`                                                                                 | Record<string, *any*>                                                                    | :heavy_minus_sign:                                                                       | N/A                                                                                      |