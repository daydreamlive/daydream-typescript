# Sd153LatentPreprocessingProcessor

## Example Usage

```typescript
import { Sd153LatentPreprocessingProcessor } from "daydream-sdk/models";

let value: Sd153LatentPreprocessingProcessor = {
  type: "latent_feedback",
};
```

## Fields

| Field                                                                            | Type                                                                             | Required                                                                         | Description                                                                      |
| -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| `type`                                                                           | [models.Sd153LatentPreprocessingType](../models/sd153latentpreprocessingtype.md) | :heavy_check_mark:                                                               | N/A                                                                              |
| `enabled`                                                                        | *boolean*                                                                        | :heavy_minus_sign:                                                               | Whether this processor is active                                                 |
| `params`                                                                         | Record<string, *any*>                                                            | :heavy_minus_sign:                                                               | N/A                                                                              |