# SDTurbo4ImagePreprocessing

List of image preprocessor configurations for image processing

## Example Usage

```typescript
import { SDTurbo4ImagePreprocessing } from "daydream-sdk/models";

let value: SDTurbo4ImagePreprocessing = {
  processors: [
    {
      type: "temporal_net_tensorrt",
    },
  ],
};
```

## Fields

| Field                                                                                            | Type                                                                                             | Required                                                                                         | Description                                                                                      |
| ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| `enabled`                                                                                        | *boolean*                                                                                        | :heavy_minus_sign:                                                                               | Whether this processor config is active                                                          |
| `processors`                                                                                     | [models.SDTurbo4ImagePreprocessingProcessor](../models/sdturbo4imagepreprocessingprocessor.md)[] | :heavy_check_mark:                                                                               | List of image processors to apply                                                                |