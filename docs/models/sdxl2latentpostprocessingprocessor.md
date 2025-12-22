# Sdxl2LatentPostprocessingProcessor

## Example Usage

```typescript
import { Sdxl2LatentPostprocessingProcessor } from "daydream-sdk/models";

let value: Sdxl2LatentPostprocessingProcessor = {
  type: "latent_feedback",
};
```

## Fields

| Field                                                                              | Type                                                                               | Required                                                                           | Description                                                                        |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `type`                                                                             | [models.Sdxl2LatentPostprocessingType](../models/sdxl2latentpostprocessingtype.md) | :heavy_check_mark:                                                                 | N/A                                                                                |
| `enabled`                                                                          | *boolean*                                                                          | :heavy_minus_sign:                                                                 | Whether this processor is active                                                   |
| `params`                                                                           | Record<string, *any*>                                                              | :heavy_minus_sign:                                                                 | N/A                                                                                |