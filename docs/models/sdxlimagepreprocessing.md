# SDXLImagePreprocessing

List of image preprocessor configurations for image processing

## Example Usage

```typescript
import { SDXLImagePreprocessing } from "daydream-sdk/models";

let value: SDXLImagePreprocessing = {
  processors: [],
};
```

## Fields

| Field                                                                                    | Type                                                                                     | Required                                                                                 | Description                                                                              |
| ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| `enabled`                                                                                | *boolean*                                                                                | :heavy_minus_sign:                                                                       | Whether this processor config is active                                                  |
| `processors`                                                                             | [models.SDXLImagePreprocessingProcessor](../models/sdxlimagepreprocessingprocessor.md)[] | :heavy_check_mark:                                                                       | List of image processors to apply                                                        |