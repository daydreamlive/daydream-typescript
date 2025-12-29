# Sdxl3ImagePostprocessingProcessor

## Example Usage

```typescript
import { Sdxl3ImagePostprocessingProcessor } from "@daydreamlive/sdk/models";

let value: Sdxl3ImagePostprocessingProcessor = {
  type: "sharpen",
};
```

## Fields

| Field                                                                            | Type                                                                             | Required                                                                         | Description                                                                      |
| -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| `type`                                                                           | [models.Sdxl3ImagePostprocessingType](../models/sdxl3imagepostprocessingtype.md) | :heavy_check_mark:                                                               | N/A                                                                              |
| `enabled`                                                                        | *boolean*                                                                        | :heavy_minus_sign:                                                               | Whether this processor is active                                                 |
| `params`                                                                         | Record<string, *any*>                                                            | :heavy_minus_sign:                                                               | N/A                                                                              |