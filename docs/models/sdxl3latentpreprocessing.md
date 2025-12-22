# Sdxl3LatentPreprocessing

List of latent preprocessor configurations for latent processing

## Example Usage

```typescript
import { Sdxl3LatentPreprocessing } from "daydream-sdk/models";

let value: Sdxl3LatentPreprocessing = {
  processors: [],
};
```

## Fields

| Field                                                                                        | Type                                                                                         | Required                                                                                     | Description                                                                                  |
| -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| `enabled`                                                                                    | *boolean*                                                                                    | :heavy_minus_sign:                                                                           | Whether this processor config is active                                                      |
| `processors`                                                                                 | [models.Sdxl3LatentPreprocessingProcessor](../models/sdxl3latentpreprocessingprocessor.md)[] | :heavy_check_mark:                                                                           | List of latent processors to apply                                                           |