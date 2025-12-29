# Sdxl3ImagePostprocessing

List of image postprocessor configurations for image processing
      ⚠️ NOTE: realesrgan_trt processor requires a restart to change because it affects resolution.
      

## Example Usage

```typescript
import { Sdxl3ImagePostprocessing } from "@daydreamlive/sdk/models";

let value: Sdxl3ImagePostprocessing = {
  processors: [
    {
      type: "mediapipe_pose",
    },
  ],
};
```

## Fields

| Field                                                                                        | Type                                                                                         | Required                                                                                     | Description                                                                                  |
| -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| `enabled`                                                                                    | *boolean*                                                                                    | :heavy_minus_sign:                                                                           | Whether this processor config is active                                                      |
| `processors`                                                                                 | [models.Sdxl3ImagePostprocessingProcessor](../models/sdxl3imagepostprocessingprocessor.md)[] | :heavy_check_mark:                                                                           | List of image processors to apply                                                            |