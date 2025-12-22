# Sd153LatentPreprocessing

List of latent preprocessor configurations for latent processing

## Example Usage

```typescript
import { Sd153LatentPreprocessing } from "daydream-sdk/models";

let value: Sd153LatentPreprocessing = {
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
| `processors`                                                                                 | [models.Sd153LatentPreprocessingProcessor](../models/sd153latentpreprocessingprocessor.md)[] | :heavy_check_mark:                                                                           | List of latent processors to apply                                                           |