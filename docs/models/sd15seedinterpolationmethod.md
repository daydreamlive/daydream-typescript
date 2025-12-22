# Sd15SeedInterpolationMethod

Method for interpolating between multiple seeds. Slerp provides smoother transitions than linear.

## Example Usage

```typescript
import { Sd15SeedInterpolationMethod } from "daydream-sdk/models";

let value: Sd15SeedInterpolationMethod = "slerp";
```

## Values

```typescript
"linear" | "slerp"
```