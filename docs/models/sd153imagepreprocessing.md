# Sd153ImagePreprocessing

List of image preprocessor configurations for image processing

## Example Usage

```typescript
import { Sd153ImagePreprocessing } from "daydream-sdk/models";

let value: Sd153ImagePreprocessing = {
  processors: [
    {
      type: "mediapipe_pose",
    },
  ],
};
```

## Fields

| Field                                                                                      | Type                                                                                       | Required                                                                                   | Description                                                                                |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| `enabled`                                                                                  | *boolean*                                                                                  | :heavy_minus_sign:                                                                         | Whether this processor config is active                                                    |
| `processors`                                                                               | [models.Sd153ImagePreprocessingProcessor](../models/sd153imagepreprocessingprocessor.md)[] | :heavy_check_mark:                                                                         | List of image processors to apply                                                          |