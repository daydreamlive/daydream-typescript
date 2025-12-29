# Sdxl1Acceleration

Acceleration method for inference. Options: "none", "xformers", "tensorrt". TensorRT provides the best performance but requires engine compilation.

## Example Usage

```typescript
import { Sdxl1Acceleration } from "@daydreamlive/sdk/models";

let value: Sdxl1Acceleration = "tensorrt";
```

## Values

This is an open enum. Unrecognized values will be captured as the `Unrecognized<string>` branded type.

```typescript
"none" | "xformers" | "tensorrt" | Unrecognized<string>
```