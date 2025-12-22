# Sd153ImagePostprocessingProcessor

## Example Usage

```typescript
import { Sd153ImagePostprocessingProcessor } from "daydream-sdk/models";

let value: Sd153ImagePostprocessingProcessor = {
  type: "canny",
};
```

## Fields

| Field                                                                            | Type                                                                             | Required                                                                         | Description                                                                      |
| -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| `type`                                                                           | [models.Sd153ImagePostprocessingType](../models/sd153imagepostprocessingtype.md) | :heavy_check_mark:                                                               | N/A                                                                              |
| `enabled`                                                                        | *boolean*                                                                        | :heavy_minus_sign:                                                               | Whether this processor is active                                                 |
| `params`                                                                         | Record<string, *any*>                                                            | :heavy_minus_sign:                                                               | N/A                                                                              |