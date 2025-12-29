# Sd152Acceleration

Acceleration method for inference. Options: "none", "xformers", "tensorrt". TensorRT provides the best performance but requires engine compilation.

## Example Usage

```typescript
import { Sd152Acceleration } from "@daydreamlive/sdk/models";

let value: Sd152Acceleration = "none";
```

## Values

```typescript
"none" | "xformers" | "tensorrt"
```