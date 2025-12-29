# SDTurbo2Acceleration

Acceleration method for inference. Options: "none", "xformers", "tensorrt". TensorRT provides the best performance but requires engine compilation.

## Example Usage

```typescript
import { SDTurbo2Acceleration } from "@daydreamlive/sdk/models";

let value: SDTurbo2Acceleration = "tensorrt";
```

## Values

```typescript
"none" | "xformers" | "tensorrt"
```