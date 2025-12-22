# SeedInterpolationMethod

Method for interpolating between multiple seeds. Slerp provides smoother transitions than linear.

## Example Usage

```typescript
import { SeedInterpolationMethod } from "daydream-sdk/models/operations";

let value: SeedInterpolationMethod = "slerp";
```

## Values

```typescript
"linear" | "slerp"
```