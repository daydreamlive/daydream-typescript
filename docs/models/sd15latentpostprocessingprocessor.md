# Sd15LatentPostprocessingProcessor

## Example Usage

```typescript
import { Sd15LatentPostprocessingProcessor } from "@daydreamlive/sdk/models";

let value: Sd15LatentPostprocessingProcessor = {
  type: "latent_feedback",
};
```

## Fields

| Field                                                                            | Type                                                                             | Required                                                                         | Description                                                                      |
| -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| `type`                                                                           | [models.Sd15LatentPostprocessingType](../models/sd15latentpostprocessingtype.md) | :heavy_check_mark:                                                               | N/A                                                                              |
| `enabled`                                                                        | *boolean*                                                                        | :heavy_minus_sign:                                                               | Whether this processor is active                                                 |
| `params`                                                                         | Record<string, *any*>                                                            | :heavy_minus_sign:                                                               | N/A                                                                              |