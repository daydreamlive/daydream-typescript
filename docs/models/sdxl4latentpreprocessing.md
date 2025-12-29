# Sdxl4LatentPreprocessing

List of latent preprocessor configurations for latent processing

## Example Usage

```typescript
import { Sdxl4LatentPreprocessing } from "@daydreamlive/sdk/models";

let value: Sdxl4LatentPreprocessing = {
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
| `processors`                                                                                 | [models.Sdxl4LatentPreprocessingProcessor](../models/sdxl4latentpreprocessingprocessor.md)[] | :heavy_check_mark:                                                                           | List of latent processors to apply                                                           |