# Sdxl2Acceleration

Acceleration method for inference. Options: "none", "xformers", "tensorrt". TensorRT provides the best performance but requires engine compilation.

## Example Usage

```typescript
import { Sdxl2Acceleration } from "@daydreamlive/sdk/models";

let value: Sdxl2Acceleration = "none";
```

## Values

```typescript
"none" | "xformers" | "tensorrt"
```