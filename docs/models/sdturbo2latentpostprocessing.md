# SDTurbo2LatentPostprocessing

List of latent postprocessor configurations for latent processing

## Example Usage

```typescript
import { SDTurbo2LatentPostprocessing } from "daydream-sdk/models";

let value: SDTurbo2LatentPostprocessing = {
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
| `processors`                                                                                         | [models.SDTurbo2LatentPostprocessingProcessor](../models/sdturbo2latentpostprocessingprocessor.md)[] | :heavy_check_mark:                                                                                   | List of latent processors to apply                                                                   |