# SDXLLatentPostprocessing

List of latent postprocessor configurations for latent processing

## Example Usage

```typescript
import { SDXLLatentPostprocessing } from "@daydreamlive/sdk/models";

let value: SDXLLatentPostprocessing = {
  processors: [
    {
      type: "latent_feedback",
    },
  ],
};
```

## Fields

| Field                                                                                        | Type                                                                                         | Required                                                                                     | Description                                                                                  |
| -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| `enabled`                                                                                    | *boolean*                                                                                    | :heavy_minus_sign:                                                                           | Whether this processor config is active                                                      |
| `processors`                                                                                 | [models.SDXLLatentPostprocessingProcessor](../models/sdxllatentpostprocessingprocessor.md)[] | :heavy_check_mark:                                                                           | List of latent processors to apply                                                           |