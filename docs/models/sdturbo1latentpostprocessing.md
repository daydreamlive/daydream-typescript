# SDTurbo1LatentPostprocessing

List of latent postprocessor configurations for latent processing

## Example Usage

```typescript
import { SDTurbo1LatentPostprocessing } from "@daydreamlive/sdk/models";

let value: SDTurbo1LatentPostprocessing = {
  processors: [
    {
      type: "latent_feedback",
    },
  ],
};
```

## Fields

| Field                                                                                                | Type                                                                                                 | Required                                                                                             | Description                                                                                          |
| ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| `enabled`                                                                                            | *boolean*                                                                                            | :heavy_minus_sign:                                                                                   | Whether this processor config is active                                                              |
| `processors`                                                                                         | [models.SDTurbo1LatentPostprocessingProcessor](../models/sdturbo1latentpostprocessingprocessor.md)[] | :heavy_check_mark:                                                                                   | List of latent processors to apply                                                                   |