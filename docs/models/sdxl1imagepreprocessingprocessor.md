# Sdxl1ImagePreprocessingProcessor

## Example Usage

```typescript
import { Sdxl1ImagePreprocessingProcessor } from "@daydreamlive/sdk/models";

let value: Sdxl1ImagePreprocessingProcessor = {
  type: "blur",
};
```

## Fields

| Field                                                                          | Type                                                                           | Required                                                                       | Description                                                                    |
| ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ |
| `type`                                                                         | [models.Sdxl1ImagePreprocessingType](../models/sdxl1imagepreprocessingtype.md) | :heavy_check_mark:                                                             | N/A                                                                            |
| `enabled`                                                                      | *boolean*                                                                      | :heavy_minus_sign:                                                             | Whether this processor is active                                               |
| `params`                                                                       | Record<string, *any*>                                                          | :heavy_minus_sign:                                                             | N/A                                                                            |