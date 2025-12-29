# SDTurbo4LatentPostprocessing

List of latent postprocessor configurations for latent processing

## Example Usage

```typescript
import { SDTurbo4LatentPostprocessing } from "@daydreamlive/sdk/models";

let value: SDTurbo4LatentPostprocessing = {
  processors: [],
};
```

## Fields

| Field                                                                                                | Type                                                                                                 | Required                                                                                             | Description                                                                                          |
| ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| `enabled`                                                                                            | *boolean*                                                                                            | :heavy_minus_sign:                                                                                   | Whether this processor config is active                                                              |
| `processors`                                                                                         | [models.SDTurbo4LatentPostprocessingProcessor](../models/sdturbo4latentpostprocessingprocessor.md)[] | :heavy_check_mark:                                                                                   | List of latent processors to apply                                                                   |