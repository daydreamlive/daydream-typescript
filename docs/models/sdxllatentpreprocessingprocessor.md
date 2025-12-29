# SDXLLatentPreprocessingProcessor

## Example Usage

```typescript
import { SDXLLatentPreprocessingProcessor } from "@daydreamlive/sdk/models";

let value: SDXLLatentPreprocessingProcessor = {
  type: "latent_feedback",
};
```

## Fields

| Field                                                                          | Type                                                                           | Required                                                                       | Description                                                                    |
| ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ |
| `type`                                                                         | [models.SDXLLatentPreprocessingType](../models/sdxllatentpreprocessingtype.md) | :heavy_check_mark:                                                             | N/A                                                                            |
| `enabled`                                                                      | *boolean*                                                                      | :heavy_minus_sign:                                                             | Whether this processor is active                                               |
| `params`                                                                       | Record<string, *any*>                                                          | :heavy_minus_sign:                                                             | N/A                                                                            |