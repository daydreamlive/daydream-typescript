# SDXLAcceleration

Acceleration method for inference. Options: "none", "xformers", "tensorrt". TensorRT provides the best performance but requires engine compilation.

## Example Usage

```typescript
import { SDXLAcceleration } from "daydream-sdk/models";

let value: SDXLAcceleration = "none";
```

## Values

```typescript
"none" | "xformers" | "tensorrt"
```