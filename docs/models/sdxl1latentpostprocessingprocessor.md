# Sdxl1LatentPostprocessingProcessor

## Example Usage

```typescript
import { Sdxl1LatentPostprocessingProcessor } from "daydream-sdk/models";

let value: Sdxl1LatentPostprocessingProcessor = {
  type: "latent_feedback",
};
```

## Fields

| Field                                                                              | Type                                                                               | Required                                                                           | Description                                                                        |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `type`                                                                             | [models.Sdxl1LatentPostprocessingType](../models/sdxl1latentpostprocessingtype.md) | :heavy_check_mark:                                                                 | N/A                                                                                |
| `enabled`                                                                          | *boolean*                                                                          | :heavy_minus_sign:                                                                 | Whether this processor is active                                                   |
| `params`                                                                           | Record<string, *any*>                                                              | :heavy_minus_sign:                                                                 | N/A                                                                                |