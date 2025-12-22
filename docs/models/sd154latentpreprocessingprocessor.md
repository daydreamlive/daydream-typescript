# Sd154LatentPreprocessingProcessor

## Example Usage

```typescript
import { Sd154LatentPreprocessingProcessor } from "daydream-sdk/models";

let value: Sd154LatentPreprocessingProcessor = {
  type: "latent_feedback",
};
```

## Fields

| Field                                                                            | Type                                                                             | Required                                                                         | Description                                                                      |
| -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| `type`                                                                           | [models.Sd154LatentPreprocessingType](../models/sd154latentpreprocessingtype.md) | :heavy_check_mark:                                                               | N/A                                                                              |
| `enabled`                                                                        | *boolean*                                                                        | :heavy_minus_sign:                                                               | Whether this processor is active                                                 |
| `params`                                                                         | Record<string, *any*>                                                            | :heavy_minus_sign:                                                               | N/A                                                                              |