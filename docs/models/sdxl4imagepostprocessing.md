# Sdxl4ImagePostprocessing

List of image postprocessor configurations for image processing
      ⚠️ NOTE: realesrgan_trt processor requires a restart to change because it affects resolution.
      

## Example Usage

```typescript
import { Sdxl4ImagePostprocessing } from "daydream-sdk/models";

let value: Sdxl4ImagePostprocessing = {
  processors: [],
};
```

## Fields

| Field                                                                                        | Type                                                                                         | Required                                                                                     | Description                                                                                  |
| -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| `enabled`                                                                                    | *boolean*                                                                                    | :heavy_minus_sign:                                                                           | Whether this processor config is active                                                      |
| `processors`                                                                                 | [models.Sdxl4ImagePostprocessingProcessor](../models/sdxl4imagepostprocessingprocessor.md)[] | :heavy_check_mark:                                                                           | List of image processors to apply                                                            |