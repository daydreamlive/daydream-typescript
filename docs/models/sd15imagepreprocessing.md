# Sd15ImagePreprocessing

List of image preprocessor configurations for image processing

## Example Usage

```typescript
import { Sd15ImagePreprocessing } from "@daydreamlive/sdk/models";

let value: Sd15ImagePreprocessing = {
  processors: [],
};
```

## Fields

| Field                                                                                    | Type                                                                                     | Required                                                                                 | Description                                                                              |
| ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| `enabled`                                                                                | *boolean*                                                                                | :heavy_minus_sign:                                                                       | Whether this processor config is active                                                  |
| `processors`                                                                             | [models.Sd15ImagePreprocessingProcessor](../models/sd15imagepreprocessingprocessor.md)[] | :heavy_check_mark:                                                                       | List of image processors to apply                                                        |