# SDXLSeedInterpolationMethod

Method for interpolating between multiple seeds. Slerp provides smoother transitions than linear.

## Example Usage

```typescript
import { SDXLSeedInterpolationMethod } from "@daydreamlive/sdk/models";

let value: SDXLSeedInterpolationMethod = "slerp";
```

## Values

```typescript
"linear" | "slerp"
```