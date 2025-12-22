# SDTurbo1LatentPostprocessingProcessor

## Example Usage

```typescript
import { SDTurbo1LatentPostprocessingProcessor } from "daydream-sdk/models";

let value: SDTurbo1LatentPostprocessingProcessor = {
  type: "latent_feedback",
};
```

## Fields

| Field                                                                                    | Type                                                                                     | Required                                                                                 | Description                                                                              |
| ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| `type`                                                                                   | [models.SDTurbo1LatentPostprocessingType](../models/sdturbo1latentpostprocessingtype.md) | :heavy_check_mark:                                                                       | N/A                                                                                      |
| `enabled`                                                                                | *boolean*                                                                                | :heavy_minus_sign:                                                                       | Whether this processor is active                                                         |
| `params`                                                                                 | Record<string, *any*>                                                                    | :heavy_minus_sign:                                                                       | N/A                                                                                      |