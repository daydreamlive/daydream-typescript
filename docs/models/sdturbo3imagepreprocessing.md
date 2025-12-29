# SDTurbo3ImagePreprocessing

List of image preprocessor configurations for image processing

## Example Usage

```typescript
import { SDTurbo3ImagePreprocessing } from "@daydreamlive/sdk/models";

let value: SDTurbo3ImagePreprocessing = {
  processors: [
    {
      type: "passthrough",
    },
  ],
};
```

## Fields

| Field                                                                                            | Type                                                                                             | Required                                                                                         | Description                                                                                      |
| ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| `enabled`                                                                                        | *boolean*                                                                                        | :heavy_minus_sign:                                                                               | Whether this processor config is active                                                          |
| `processors`                                                                                     | [models.SDTurbo3ImagePreprocessingProcessor](../models/sdturbo3imagepreprocessingprocessor.md)[] | :heavy_check_mark:                                                                               | List of image processors to apply                                                                |