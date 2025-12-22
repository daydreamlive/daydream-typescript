# Sdxl4ImagePreprocessingProcessor

## Example Usage

```typescript
import { Sdxl4ImagePreprocessingProcessor } from "daydream-sdk/models";

let value: Sdxl4ImagePreprocessingProcessor = {
  type: "mediapipe_segmentation",
};
```

## Fields

| Field                                                                          | Type                                                                           | Required                                                                       | Description                                                                    |
| ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ |
| `type`                                                                         | [models.Sdxl4ImagePreprocessingType](../models/sdxl4imagepreprocessingtype.md) | :heavy_check_mark:                                                             | N/A                                                                            |
| `enabled`                                                                      | *boolean*                                                                      | :heavy_minus_sign:                                                             | Whether this processor is active                                               |
| `params`                                                                       | Record<string, *any*>                                                          | :heavy_minus_sign:                                                             | N/A                                                                            |