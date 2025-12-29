# SDXLImagePreprocessingProcessor

## Example Usage

```typescript
import { SDXLImagePreprocessingProcessor } from "@daydreamlive/sdk/models";

let value: SDXLImagePreprocessingProcessor = {
  type: "soft_edge",
};
```

## Fields

| Field                                                                        | Type                                                                         | Required                                                                     | Description                                                                  |
| ---------------------------------------------------------------------------- | ---------------------------------------------------------------------------- | ---------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| `type`                                                                       | [models.SDXLImagePreprocessingType](../models/sdxlimagepreprocessingtype.md) | :heavy_check_mark:                                                           | N/A                                                                          |
| `enabled`                                                                    | *boolean*                                                                    | :heavy_minus_sign:                                                           | Whether this processor is active                                             |
| `params`                                                                     | Record<string, *any*>                                                        | :heavy_minus_sign:                                                           | N/A                                                                          |