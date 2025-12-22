# Sdxl2ImagePostprocessingProcessor

## Example Usage

```typescript
import { Sdxl2ImagePostprocessingProcessor } from "daydream-sdk/models";

let value: Sdxl2ImagePostprocessingProcessor = {
  type: "external",
};
```

## Fields

| Field                                                                            | Type                                                                             | Required                                                                         | Description                                                                      |
| -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| `type`                                                                           | [models.Sdxl2ImagePostprocessingType](../models/sdxl2imagepostprocessingtype.md) | :heavy_check_mark:                                                               | N/A                                                                              |
| `enabled`                                                                        | *boolean*                                                                        | :heavy_minus_sign:                                                               | Whether this processor is active                                                 |
| `params`                                                                         | Record<string, *any*>                                                            | :heavy_minus_sign:                                                               | N/A                                                                              |