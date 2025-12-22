# Sdxl1LatentPreprocessing

List of latent preprocessor configurations for latent processing

## Example Usage

```typescript
import { Sdxl1LatentPreprocessing } from "daydream-sdk/models";

let value: Sdxl1LatentPreprocessing = {
  processors: [
    {
      type: "latent_feedback",
    },
  ],
};
```

## Fields

| Field                                                                                        | Type                                                                                         | Required                                                                                     | Description                                                                                  |
| -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| `enabled`                                                                                    | *boolean*                                                                                    | :heavy_minus_sign:                                                                           | Whether this processor config is active                                                      |
| `processors`                                                                                 | [models.Sdxl1LatentPreprocessingProcessor](../models/sdxl1latentpreprocessingprocessor.md)[] | :heavy_check_mark:                                                                           | List of latent processors to apply                                                           |