# Sdxl3SeedInterpolationMethod

Method for interpolating between multiple seeds. Slerp provides smoother transitions than linear.

## Example Usage

```typescript
import { Sdxl3SeedInterpolationMethod } from "daydream-sdk/models";

let value: Sdxl3SeedInterpolationMethod = "linear";
```

## Values

This is an open enum. Unrecognized values will be captured as the `Unrecognized<string>` branded type.

```typescript
"linear" | "slerp" | Unrecognized<string>
```