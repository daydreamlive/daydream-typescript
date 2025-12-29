# SDTurbo2Preprocessor

Preprocessor to apply to input frames before feeding to the ControlNet. Must be one of the supported preprocessors.

## Example Usage

```typescript
import { SDTurbo2Preprocessor } from "@daydreamlive/sdk/models";

let value: SDTurbo2Preprocessor = "soft_edge";
```

## Values

```typescript
"blur" | "canny" | "depth" | "depth_tensorrt" | "external" | "feedback" | "hed" | "lineart" | "mediapipe_pose" | "mediapipe_segmentation" | "openpose" | "passthrough" | "pose_tensorrt" | "realesrgan_trt" | "sharpen" | "soft_edge" | "standard_lineart" | "temporal_net_tensorrt" | "upscale"
```