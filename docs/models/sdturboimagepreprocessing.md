# SDTurboImagePreprocessing

List of image preprocessor configurations for image processing

## Example Usage

```typescript
import { SDTurboImagePreprocessing } from "daydream-sdk/models";

let value: SDTurboImagePreprocessing = {
  processors: [
    {
      type: "canny",
    },
  ],
};
```

## Fields

| Field                                                                                          | Type                                                                                           | Required                                                                                       | Description                                                                                    |
| ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| `enabled`                                                                                      | *boolean*                                                                                      | :heavy_minus_sign:                                                                             | Whether this processor config is active                                                        |
| `processors`                                                                                   | [models.SDTurboImagePreprocessingProcessor](../models/sdturboimagepreprocessingprocessor.md)[] | :heavy_check_mark:                                                                             | List of image processors to apply                                                              |