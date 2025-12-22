# SDTurbo1ImagePostprocessingProcessor

## Example Usage

```typescript
import { SDTurbo1ImagePostprocessingProcessor } from "daydream-sdk/models";

let value: SDTurbo1ImagePostprocessingProcessor = {
  type: "passthrough",
};
```

## Fields

| Field                                                                                  | Type                                                                                   | Required                                                                               | Description                                                                            |
| -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| `type`                                                                                 | [models.SDTurbo1ImagePostprocessingType](../models/sdturbo1imagepostprocessingtype.md) | :heavy_check_mark:                                                                     | N/A                                                                                    |
| `enabled`                                                                              | *boolean*                                                                              | :heavy_minus_sign:                                                                     | Whether this processor is active                                                       |
| `params`                                                                               | Record<string, *any*>                                                                  | :heavy_minus_sign:                                                                     | N/A                                                                                    |