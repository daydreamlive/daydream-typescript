# Sd15LatentPostprocessing

List of latent postprocessor configurations for latent processing

## Example Usage

```typescript
import { Sd15LatentPostprocessing } from "@daydreamlive/sdk/models";

let value: Sd15LatentPostprocessing = {
  processors: [],
};
```

## Fields

| Field                                                                                        | Type                                                                                         | Required                                                                                     | Description                                                                                  |
| -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| `enabled`                                                                                    | *boolean*                                                                                    | :heavy_minus_sign:                                                                           | Whether this processor config is active                                                      |
| `processors`                                                                                 | [models.Sd15LatentPostprocessingProcessor](../models/sd15latentpostprocessingprocessor.md)[] | :heavy_check_mark:                                                                           | List of latent processors to apply                                                           |