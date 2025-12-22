# SDTurbo3LatentPostprocessing

List of latent postprocessor configurations for latent processing

## Example Usage

```typescript
import { SDTurbo3LatentPostprocessing } from "daydream-sdk/models";

let value: SDTurbo3LatentPostprocessing = {
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
| `processors`                                                                                         | [models.SDTurbo3LatentPostprocessingProcessor](../models/sdturbo3latentpostprocessingprocessor.md)[] | :heavy_check_mark:                                                                                   | List of latent processors to apply                                                                   |