# SDTurbo2ImagePreprocessing

List of image preprocessor configurations for image processing

## Example Usage

```typescript
import { SDTurbo2ImagePreprocessing } from "daydream-sdk/models";

let value: SDTurbo2ImagePreprocessing = {
  processors: [
    {
      type: "external",
    },
  ],
};
```

## Fields

| Field                                                                                            | Type                                                                                             | Required                                                                                         | Description                                                                                      |
| ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| `enabled`                                                                                        | *boolean*                                                                                        | :heavy_minus_sign:                                                                               | Whether this processor config is active                                                          |
| `processors`                                                                                     | [models.SDTurbo2ImagePreprocessingProcessor](../models/sdturbo2imagepreprocessingprocessor.md)[] | :heavy_check_mark:                                                                               | List of image processors to apply                                                                |