# Sd151LatentPreprocessing

List of latent preprocessor configurations for latent processing

## Example Usage

```typescript
import { Sd151LatentPreprocessing } from "@daydreamlive/sdk/models";

let value: Sd151LatentPreprocessing = {
  processors: [],
};
```

## Fields

| Field                                                                                        | Type                                                                                         | Required                                                                                     | Description                                                                                  |
| -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| `enabled`                                                                                    | *boolean*                                                                                    | :heavy_minus_sign:                                                                           | Whether this processor config is active                                                      |
| `processors`                                                                                 | [models.Sd151LatentPreprocessingProcessor](../models/sd151latentpreprocessingprocessor.md)[] | :heavy_check_mark:                                                                           | List of latent processors to apply                                                           |