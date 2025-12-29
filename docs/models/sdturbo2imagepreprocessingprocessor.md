# SDTurbo2ImagePreprocessingProcessor

## Example Usage

```typescript
import { SDTurbo2ImagePreprocessingProcessor } from "@daydreamlive/sdk/models";

let value: SDTurbo2ImagePreprocessingProcessor = {
  type: "sharpen",
};
```

## Fields

| Field                                                                                | Type                                                                                 | Required                                                                             | Description                                                                          |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
| `type`                                                                               | [models.SDTurbo2ImagePreprocessingType](../models/sdturbo2imagepreprocessingtype.md) | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `enabled`                                                                            | *boolean*                                                                            | :heavy_minus_sign:                                                                   | Whether this processor is active                                                     |
| `params`                                                                             | Record<string, *any*>                                                                | :heavy_minus_sign:                                                                   | N/A                                                                                  |