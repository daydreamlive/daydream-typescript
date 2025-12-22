# SDXLImagePostprocessingProcessor

## Example Usage

```typescript
import { SDXLImagePostprocessingProcessor } from "daydream-sdk/models";

let value: SDXLImagePostprocessingProcessor = {
  type: "depth",
};
```

## Fields

| Field                                                                          | Type                                                                           | Required                                                                       | Description                                                                    |
| ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ |
| `type`                                                                         | [models.SDXLImagePostprocessingType](../models/sdxlimagepostprocessingtype.md) | :heavy_check_mark:                                                             | N/A                                                                            |
| `enabled`                                                                      | *boolean*                                                                      | :heavy_minus_sign:                                                             | Whether this processor is active                                               |
| `params`                                                                       | Record<string, *any*>                                                          | :heavy_minus_sign:                                                             | N/A                                                                            |