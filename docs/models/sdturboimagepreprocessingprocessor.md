# SDTurboImagePreprocessingProcessor

## Example Usage

```typescript
import { SDTurboImagePreprocessingProcessor } from "@daydreamlive/sdk/models";

let value: SDTurboImagePreprocessingProcessor = {
  type: "canny",
};
```

## Fields

| Field                                                                              | Type                                                                               | Required                                                                           | Description                                                                        |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| `type`                                                                             | [models.SDTurboImagePreprocessingType](../models/sdturboimagepreprocessingtype.md) | :heavy_check_mark:                                                                 | N/A                                                                                |
| `enabled`                                                                          | *boolean*                                                                          | :heavy_minus_sign:                                                                 | Whether this processor is active                                                   |
| `params`                                                                           | Record<string, *any*>                                                              | :heavy_minus_sign:                                                                 | N/A                                                                                |