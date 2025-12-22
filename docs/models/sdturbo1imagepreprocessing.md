# SDTurbo1ImagePreprocessing

List of image preprocessor configurations for image processing

## Example Usage

```typescript
import { SDTurbo1ImagePreprocessing } from "daydream-sdk/models";

let value: SDTurbo1ImagePreprocessing = {
  processors: [],
};
```

## Fields

| Field                                                                                            | Type                                                                                             | Required                                                                                         | Description                                                                                      |
| ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| `enabled`                                                                                        | *boolean*                                                                                        | :heavy_minus_sign:                                                                               | Whether this processor config is active                                                          |
| `processors`                                                                                     | [models.SDTurbo1ImagePreprocessingProcessor](../models/sdturbo1imagepreprocessingprocessor.md)[] | :heavy_check_mark:                                                                               | List of image processors to apply                                                                |