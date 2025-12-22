# Sd154LatentPostprocessingProcessor

## Example Usage

```typescript
import { Sd154LatentPostprocessingProcessor } from "daydream-sdk/models";

let value: Sd154LatentPostprocessingProcessor = {
  type: "latent_feedback",
};
```

## Fields

| Field                                                                              | Type                                                                               | Required                                                                           | Description                                                                        |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `type`                                                                             | [models.Sd154LatentPostprocessingType](../models/sd154latentpostprocessingtype.md) | :heavy_check_mark:                                                                 | N/A                                                                                |
| `enabled`                                                                          | *boolean*                                                                          | :heavy_minus_sign:                                                                 | Whether this processor is active                                                   |
| `params`                                                                           | Record<string, *any*>                                                              | :heavy_minus_sign:                                                                 | N/A                                                                                |