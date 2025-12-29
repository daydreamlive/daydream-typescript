# SDTurboAcceleration

Acceleration method for inference. Options: "none", "xformers", "tensorrt". TensorRT provides the best performance but requires engine compilation.

## Example Usage

```typescript
import { SDTurboAcceleration } from "@daydreamlive/sdk/models";

let value: SDTurboAcceleration = "tensorrt";
```

## Values

```typescript
"none" | "xformers" | "tensorrt"
```