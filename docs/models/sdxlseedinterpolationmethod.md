# SDXLSeedInterpolationMethod

Method for interpolating between multiple seeds. Slerp provides smoother transitions than linear.

## Example Usage

```typescript
import { SDXLSeedInterpolationMethod } from "daydream-sdk/models";

let value: SDXLSeedInterpolationMethod = "slerp";
```

## Values

```typescript
"linear" | "slerp"
```