# SDTurbo1ImagePreprocessingProcessor

## Example Usage

```typescript
import { SDTurbo1ImagePreprocessingProcessor } from "daydream-sdk/models";

let value: SDTurbo1ImagePreprocessingProcessor = {
  type: "mediapipe_segmentation",
};
```

## Fields

| Field                                                                                | Type                                                                                 | Required                                                                             | Description                                                                          |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
| `type`                                                                               | [models.SDTurbo1ImagePreprocessingType](../models/sdturbo1imagepreprocessingtype.md) | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `enabled`                                                                            | *boolean*                                                                            | :heavy_minus_sign:                                                                   | Whether this processor is active                                                     |
| `params`                                                                             | Record<string, *any*>                                                                | :heavy_minus_sign:                                                                   | N/A                                                                                  |