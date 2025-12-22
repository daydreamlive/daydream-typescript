# SDTurboLatentPostprocessingProcessor

## Example Usage

```typescript
import { SDTurboLatentPostprocessingProcessor } from "daydream-sdk/models";

let value: SDTurboLatentPostprocessingProcessor = {
  type: "latent_feedback",
};
```

## Fields

| Field                                                                                  | Type                                                                                   | Required                                                                               | Description                                                                            |
| -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| `type`                                                                                 | [models.SDTurboLatentPostprocessingType](../models/sdturbolatentpostprocessingtype.md) | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `enabled`                                                                              | *boolean*                                                                              | :heavy_minus_sign:                                                                     | Whether this processor is active                                                       |
| `params`                                                                               | Record<string, *any*>                                                                  | :heavy_minus_sign:                                                                     | N/A                                                                                    |