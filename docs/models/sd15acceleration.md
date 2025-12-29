# Sd15Acceleration

Acceleration method for inference. Options: "none", "xformers", "tensorrt". TensorRT provides the best performance but requires engine compilation.

## Example Usage

```typescript
import { Sd15Acceleration } from "@daydreamlive/sdk/models";

let value: Sd15Acceleration = "tensorrt";
```

## Values

```typescript
"none" | "xformers" | "tensorrt"
```