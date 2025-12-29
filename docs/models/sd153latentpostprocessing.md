# Sd153LatentPostprocessing

List of latent postprocessor configurations for latent processing

## Example Usage

```typescript
import { Sd153LatentPostprocessing } from "@daydreamlive/sdk/models";

let value: Sd153LatentPostprocessing = {
  processors: [],
};
```

## Fields

| Field                                                                                          | Type                                                                                           | Required                                                                                       | Description                                                                                    |
| ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| `enabled`                                                                                      | *boolean*                                                                                      | :heavy_minus_sign:                                                                             | Whether this processor config is active                                                        |
| `processors`                                                                                   | [models.Sd153LatentPostprocessingProcessor](../models/sd153latentpostprocessingprocessor.md)[] | :heavy_check_mark:                                                                             | List of latent processors to apply                                                             |