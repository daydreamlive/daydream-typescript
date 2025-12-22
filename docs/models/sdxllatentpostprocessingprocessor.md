# SDXLLatentPostprocessingProcessor

## Example Usage

```typescript
import { SDXLLatentPostprocessingProcessor } from "daydream-sdk/models";

let value: SDXLLatentPostprocessingProcessor = {
  type: "latent_feedback",
};
```

## Fields

| Field                                                                            | Type                                                                             | Required                                                                         | Description                                                                      |
| -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| `type`                                                                           | [models.SDXLLatentPostprocessingType](../models/sdxllatentpostprocessingtype.md) | :heavy_check_mark:                                                               | N/A                                                                              |
| `enabled`                                                                        | *boolean*                                                                        | :heavy_minus_sign:                                                               | Whether this processor is active                                                 |
| `params`                                                                         | Record<string, *any*>                                                            | :heavy_minus_sign:                                                               | N/A                                                                              |