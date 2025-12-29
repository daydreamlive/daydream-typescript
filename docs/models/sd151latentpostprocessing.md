# Sd151LatentPostprocessing

List of latent postprocessor configurations for latent processing

## Example Usage

```typescript
import { Sd151LatentPostprocessing } from "@daydreamlive/sdk/models";

let value: Sd151LatentPostprocessing = {
  processors: [
    {
      type: "latent_feedback",
    },
  ],
};
```

## Fields

| Field                                                                                          | Type                                                                                           | Required                                                                                       | Description                                                                                    |
| ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| `enabled`                                                                                      | *boolean*                                                                                      | :heavy_minus_sign:                                                                             | Whether this processor config is active                                                        |
| `processors`                                                                                   | [models.Sd151LatentPostprocessingProcessor](../models/sd151latentpostprocessingprocessor.md)[] | :heavy_check_mark:                                                                             | List of latent processors to apply                                                             |