# Sdxl4ImagePostprocessingProcessor

## Example Usage

```typescript
import { Sdxl4ImagePostprocessingProcessor } from "@daydreamlive/sdk/models";

let value: Sdxl4ImagePostprocessingProcessor = {
  type: "lineart",
};
```

## Fields

| Field                                                                            | Type                                                                             | Required                                                                         | Description                                                                      |
| -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| `type`                                                                           | [models.Sdxl4ImagePostprocessingType](../models/sdxl4imagepostprocessingtype.md) | :heavy_check_mark:                                                               | N/A                                                                              |
| `enabled`                                                                        | *boolean*                                                                        | :heavy_minus_sign:                                                               | Whether this processor is active                                                 |
| `params`                                                                         | Record<string, *any*>                                                            | :heavy_minus_sign:                                                               | N/A                                                                              |