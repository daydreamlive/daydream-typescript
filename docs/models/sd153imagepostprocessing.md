# Sd153ImagePostprocessing

List of image postprocessor configurations for image processing
      ⚠️ NOTE: realesrgan_trt processor requires a restart to change because it affects resolution.
      

## Example Usage

```typescript
import { Sd153ImagePostprocessing } from "@daydreamlive/sdk/models";

let value: Sd153ImagePostprocessing = {
  processors: [
    {
      type: "passthrough",
    },
  ],
};
```

## Fields

| Field                                                                                        | Type                                                                                         | Required                                                                                     | Description                                                                                  |
| -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| `enabled`                                                                                    | *boolean*                                                                                    | :heavy_minus_sign:                                                                           | Whether this processor config is active                                                      |
| `processors`                                                                                 | [models.Sd153ImagePostprocessingProcessor](../models/sd153imagepostprocessingprocessor.md)[] | :heavy_check_mark:                                                                           | List of image processors to apply                                                            |