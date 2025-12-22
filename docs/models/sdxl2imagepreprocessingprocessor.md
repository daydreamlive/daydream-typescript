# Sdxl2ImagePreprocessingProcessor

## Example Usage

```typescript
import { Sdxl2ImagePreprocessingProcessor } from "daydream-sdk/models";

let value: Sdxl2ImagePreprocessingProcessor = {
  type: "hed",
};
```

## Fields

| Field                                                                          | Type                                                                           | Required                                                                       | Description                                                                    |
| ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ |
| `type`                                                                         | [models.Sdxl2ImagePreprocessingType](../models/sdxl2imagepreprocessingtype.md) | :heavy_check_mark:                                                             | N/A                                                                            |
| `enabled`                                                                      | *boolean*                                                                      | :heavy_minus_sign:                                                             | Whether this processor is active                                               |
| `params`                                                                       | Record<string, *any*>                                                          | :heavy_minus_sign:                                                             | N/A                                                                            |