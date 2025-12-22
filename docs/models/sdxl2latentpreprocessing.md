# Sdxl2LatentPreprocessing

List of latent preprocessor configurations for latent processing

## Example Usage

```typescript
import { Sdxl2LatentPreprocessing } from "daydream-sdk/models";

let value: Sdxl2LatentPreprocessing = {
  processors: [],
};
```

## Fields

| Field                                                                                        | Type                                                                                         | Required                                                                                     | Description                                                                                  |
| -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| `enabled`                                                                                    | *boolean*                                                                                    | :heavy_minus_sign:                                                                           | Whether this processor config is active                                                      |
| `processors`                                                                                 | [models.Sdxl2LatentPreprocessingProcessor](../models/sdxl2latentpreprocessingprocessor.md)[] | :heavy_check_mark:                                                                           | List of latent processors to apply                                                           |