# Sd152ImagePostprocessing

List of image postprocessor configurations for image processing
      ⚠️ NOTE: realesrgan_trt processor requires a restart to change because it affects resolution.
      

## Example Usage

```typescript
import { Sd152ImagePostprocessing } from "@daydreamlive/sdk/models";

let value: Sd152ImagePostprocessing = {
  processors: [],
};
```

## Fields

| Field                                                                                        | Type                                                                                         | Required                                                                                     | Description                                                                                  |
| -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| `enabled`                                                                                    | *boolean*                                                                                    | :heavy_minus_sign:                                                                           | Whether this processor config is active                                                      |
| `processors`                                                                                 | [models.Sd152ImagePostprocessingProcessor](../models/sd152imagepostprocessingprocessor.md)[] | :heavy_check_mark:                                                                           | List of image processors to apply                                                            |