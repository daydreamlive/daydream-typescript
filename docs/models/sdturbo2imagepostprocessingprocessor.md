# SDTurbo2ImagePostprocessingProcessor

## Example Usage

```typescript
import { SDTurbo2ImagePostprocessingProcessor } from "daydream-sdk/models";

let value: SDTurbo2ImagePostprocessingProcessor = {
  type: "upscale",
};
```

## Fields

| Field                                                                                  | Type                                                                                   | Required                                                                               | Description                                                                            |
| -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| `type`                                                                                 | [models.SDTurbo2ImagePostprocessingType](../models/sdturbo2imagepostprocessingtype.md) | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `enabled`                                                                              | *boolean*                                                                              | :heavy_minus_sign:                                                                     | Whether this processor is active                                                       |
| `params`                                                                               | Record<string, *any*>                                                                  | :heavy_minus_sign:                                                                     | N/A                                                                                    |