# Sd153LatentPostprocessingProcessor

## Example Usage

```typescript
import { Sd153LatentPostprocessingProcessor } from "@daydreamlive/sdk/models";

let value: Sd153LatentPostprocessingProcessor = {
  type: "latent_feedback",
};
```

## Fields

| Field                                                                              | Type                                                                               | Required                                                                           | Description                                                                        |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `type`                                                                             | [models.Sd153LatentPostprocessingType](../models/sd153latentpostprocessingtype.md) | :heavy_check_mark:                                                                 | N/A                                                                                |
| `enabled`                                                                          | *boolean*                                                                          | :heavy_minus_sign:                                                                 | Whether this processor is active                                                   |
| `params`                                                                           | Record<string, *any*>                                                              | :heavy_minus_sign:                                                                 | N/A                                                                                |