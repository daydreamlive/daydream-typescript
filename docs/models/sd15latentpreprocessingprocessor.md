# Sd15LatentPreprocessingProcessor

## Example Usage

```typescript
import { Sd15LatentPreprocessingProcessor } from "@daydreamlive/sdk/models";

let value: Sd15LatentPreprocessingProcessor = {
  type: "latent_feedback",
};
```

## Fields

| Field                                                                          | Type                                                                           | Required                                                                       | Description                                                                    |
| ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ |
| `type`                                                                         | [models.Sd15LatentPreprocessingType](../models/sd15latentpreprocessingtype.md) | :heavy_check_mark:                                                             | N/A                                                                            |
| `enabled`                                                                      | *boolean*                                                                      | :heavy_minus_sign:                                                             | Whether this processor is active                                               |
| `params`                                                                       | Record<string, *any*>                                                          | :heavy_minus_sign:                                                             | N/A                                                                            |