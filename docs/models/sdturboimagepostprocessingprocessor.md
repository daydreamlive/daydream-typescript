# SDTurboImagePostprocessingProcessor

## Example Usage

```typescript
import { SDTurboImagePostprocessingProcessor } from "@daydreamlive/sdk/models";

let value: SDTurboImagePostprocessingProcessor = {
  type: "hed",
};
```

## Fields

| Field                                                                                | Type                                                                                 | Required                                                                             | Description                                                                          |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
| `type`                                                                               | [models.SDTurboImagePostprocessingType](../models/sdturboimagepostprocessingtype.md) | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `enabled`                                                                            | *boolean*                                                                            | :heavy_minus_sign:                                                                   | Whether this processor is active                                                     |
| `params`                                                                             | Record<string, *any*>                                                                | :heavy_minus_sign:                                                                   | N/A                                                                                  |