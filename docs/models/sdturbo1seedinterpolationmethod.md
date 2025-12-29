# SDTurbo1SeedInterpolationMethod

Method for interpolating between multiple seeds. Slerp provides smoother transitions than linear.

## Example Usage

```typescript
import { SDTurbo1SeedInterpolationMethod } from "@daydreamlive/sdk/models";

let value: SDTurbo1SeedInterpolationMethod = "slerp";
```

## Values

This is an open enum. Unrecognized values will be captured as the `Unrecognized<string>` branded type.

```typescript
"linear" | "slerp" | Unrecognized<string>
```