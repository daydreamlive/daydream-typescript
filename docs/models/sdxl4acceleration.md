# Sdxl4Acceleration

Acceleration method for inference. Options: "none", "xformers", "tensorrt". TensorRT provides the best performance but requires engine compilation.

## Example Usage

```typescript
import { Sdxl4Acceleration } from "@daydreamlive/sdk/models";

let value: Sdxl4Acceleration = "none";
```

## Values

This is an open enum. Unrecognized values will be captured as the `Unrecognized<string>` branded type.

```typescript
"none" | "xformers" | "tensorrt" | Unrecognized<string>
```