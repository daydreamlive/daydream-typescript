# Sd152LatentPostprocessing

List of latent postprocessor configurations for latent processing

## Example Usage

```typescript
import { Sd152LatentPostprocessing } from "@daydreamlive/sdk/models";

let value: Sd152LatentPostprocessing = {
  processors: [],
};
```

## Fields

| Field                                                                                          | Type                                                                                           | Required                                                                                       | Description                                                                                    |
| ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| `enabled`                                                                                      | *boolean*                                                                                      | :heavy_minus_sign:                                                                             | Whether this processor config is active                                                        |
| `processors`                                                                                   | [models.Sd152LatentPostprocessingProcessor](../models/sd152latentpostprocessingprocessor.md)[] | :heavy_check_mark:                                                                             | List of latent processors to apply                                                             |