# Sd15ImagePreprocessingProcessor

## Example Usage

```typescript
import { Sd15ImagePreprocessingProcessor } from "daydream-sdk/models";

let value: Sd15ImagePreprocessingProcessor = {
  type: "realesrgan_trt",
};
```

## Fields

| Field                                                                        | Type                                                                         | Required                                                                     | Description                                                                  |
| ---------------------------------------------------------------------------- | ---------------------------------------------------------------------------- | ---------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| `type`                                                                       | [models.Sd15ImagePreprocessingType](../models/sd15imagepreprocessingtype.md) | :heavy_check_mark:                                                           | N/A                                                                          |
| `enabled`                                                                    | *boolean*                                                                    | :heavy_minus_sign:                                                           | Whether this processor is active                                             |
| `params`                                                                     | Record<string, *any*>                                                        | :heavy_minus_sign:                                                           | N/A                                                                          |