# SDTurbo3ImagePreprocessingProcessor

## Example Usage

```typescript
import { SDTurbo3ImagePreprocessingProcessor } from "@daydreamlive/sdk/models";

let value: SDTurbo3ImagePreprocessingProcessor = {
  type: "mediapipe_pose",
};
```

## Fields

| Field                                                                                | Type                                                                                 | Required                                                                             | Description                                                                          |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
| `type`                                                                               | [models.SDTurbo3ImagePreprocessingType](../models/sdturbo3imagepreprocessingtype.md) | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `enabled`                                                                            | *boolean*                                                                            | :heavy_minus_sign:                                                                   | Whether this processor is active                                                     |
| `params`                                                                             | Record<string, *any*>                                                                | :heavy_minus_sign:                                                                   | N/A                                                                                  |