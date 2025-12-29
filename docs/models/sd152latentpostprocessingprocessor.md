# Sd152LatentPostprocessingProcessor

## Example Usage

```typescript
import { Sd152LatentPostprocessingProcessor } from "@daydreamlive/sdk/models";

let value: Sd152LatentPostprocessingProcessor = {
  type: "latent_feedback",
};
```

## Fields

| Field                                                                              | Type                                                                               | Required                                                                           | Description                                                                        |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `type`                                                                             | [models.Sd152LatentPostprocessingType](../models/sd152latentpostprocessingtype.md) | :heavy_check_mark:                                                                 | N/A                                                                                |
| `enabled`                                                                          | *boolean*                                                                          | :heavy_minus_sign:                                                                 | Whether this processor is active                                                   |
| `params`                                                                           | Record<string, *any*>                                                              | :heavy_minus_sign:                                                                 | N/A                                                                                |