# Sdxl3ImagePreprocessingProcessor

## Example Usage

```typescript
import { Sdxl3ImagePreprocessingProcessor } from "daydream-sdk/models";

let value: Sdxl3ImagePreprocessingProcessor = {
  type: "canny",
};
```

## Fields

| Field                                                                          | Type                                                                           | Required                                                                       | Description                                                                    |
| ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ |
| `type`                                                                         | [models.Sdxl3ImagePreprocessingType](../models/sdxl3imagepreprocessingtype.md) | :heavy_check_mark:                                                             | N/A                                                                            |
| `enabled`                                                                      | *boolean*                                                                      | :heavy_minus_sign:                                                             | Whether this processor is active                                               |
| `params`                                                                       | Record<string, *any*>                                                          | :heavy_minus_sign:                                                             | N/A                                                                            |