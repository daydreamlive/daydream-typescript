# Sdxl2LatentPostprocessing

List of latent postprocessor configurations for latent processing

## Example Usage

```typescript
import { Sdxl2LatentPostprocessing } from "@daydreamlive/sdk/models";

let value: Sdxl2LatentPostprocessing = {
  processors: [],
};
```

## Fields

| Field                                                                                          | Type                                                                                           | Required                                                                                       | Description                                                                                    |
| ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| `enabled`                                                                                      | *boolean*                                                                                      | :heavy_minus_sign:                                                                             | Whether this processor config is active                                                        |
| `processors`                                                                                   | [models.Sdxl2LatentPostprocessingProcessor](../models/sdxl2latentpostprocessingprocessor.md)[] | :heavy_check_mark:                                                                             | List of latent processors to apply                                                             |