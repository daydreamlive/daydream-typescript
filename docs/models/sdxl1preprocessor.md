# Sdxl1Preprocessor

Preprocessor to apply to input frames before feeding to the ControlNet. Must be one of the supported preprocessors.

## Example Usage

```typescript
import { Sdxl1Preprocessor } from "@daydreamlive/sdk/models";

let value: Sdxl1Preprocessor = "realesrgan_trt";
```

## Values

This is an open enum. Unrecognized values will be captured as the `Unrecognized<string>` branded type.

```typescript
"blur" | "canny" | "depth" | "depth_tensorrt" | "external" | "feedback" | "hed" | "lineart" | "mediapipe_pose" | "mediapipe_segmentation" | "openpose" | "passthrough" | "pose_tensorrt" | "realesrgan_trt" | "sharpen" | "soft_edge" | "standard_lineart" | "temporal_net_tensorrt" | "upscale" | Unrecognized<string>
```