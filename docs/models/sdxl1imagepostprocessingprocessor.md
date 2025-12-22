# Sdxl1ImagePostprocessingProcessor

## Example Usage

```typescript
import { Sdxl1ImagePostprocessingProcessor } from "daydream-sdk/models";

let value: Sdxl1ImagePostprocessingProcessor = {
  type: "depth",
};
```

## Fields

| Field                                                                            | Type                                                                             | Required                                                                         | Description                                                                      |
| -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| `type`                                                                           | [models.Sdxl1ImagePostprocessingType](../models/sdxl1imagepostprocessingtype.md) | :heavy_check_mark:                                                               | N/A                                                                              |
| `enabled`                                                                        | *boolean*                                                                        | :heavy_minus_sign:                                                               | Whether this processor is active                                                 |
| `params`                                                                         | Record<string, *any*>                                                            | :heavy_minus_sign:                                                               | N/A                                                                              |