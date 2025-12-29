# Sdxl2SeedInterpolationMethod

Method for interpolating between multiple seeds. Slerp provides smoother transitions than linear.

## Example Usage

```typescript
import { Sdxl2SeedInterpolationMethod } from "@daydreamlive/sdk/models";

let value: Sdxl2SeedInterpolationMethod = "linear";
```

## Values

```typescript
"linear" | "slerp"
```