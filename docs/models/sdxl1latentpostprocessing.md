# Sdxl1LatentPostprocessing

List of latent postprocessor configurations for latent processing

## Example Usage

```typescript
import { Sdxl1LatentPostprocessing } from "@daydreamlive/sdk/models";

let value: Sdxl1LatentPostprocessing = {
  processors: [],
};
```

## Fields

| Field                                                                                          | Type                                                                                           | Required                                                                                       | Description                                                                                    |
| ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| `enabled`                                                                                      | *boolean*                                                                                      | :heavy_minus_sign:                                                                             | Whether this processor config is active                                                        |
| `processors`                                                                                   | [models.Sdxl1LatentPostprocessingProcessor](../models/sdxl1latentpostprocessingprocessor.md)[] | :heavy_check_mark:                                                                             | List of latent processors to apply                                                             |