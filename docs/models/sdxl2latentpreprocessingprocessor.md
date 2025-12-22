# Sdxl2LatentPreprocessingProcessor

## Example Usage

```typescript
import { Sdxl2LatentPreprocessingProcessor } from "daydream-sdk/models";

let value: Sdxl2LatentPreprocessingProcessor = {
  type: "latent_feedback",
};
```

## Fields

| Field                                                                            | Type                                                                             | Required                                                                         | Description                                                                      |
| -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| `type`                                                                           | [models.Sdxl2LatentPreprocessingType](../models/sdxl2latentpreprocessingtype.md) | :heavy_check_mark:                                                               | N/A                                                                              |
| `enabled`                                                                        | *boolean*                                                                        | :heavy_minus_sign:                                                               | Whether this processor is active                                                 |
| `params`                                                                         | Record<string, *any*>                                                            | :heavy_minus_sign:                                                               | N/A                                                                              |