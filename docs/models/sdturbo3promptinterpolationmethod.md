# SDTurbo3PromptInterpolationMethod

Method for interpolating between multiple prompts. Slerp provides smoother transitions than linear.

## Example Usage

```typescript
import { SDTurbo3PromptInterpolationMethod } from "@daydreamlive/sdk/models";

let value: SDTurbo3PromptInterpolationMethod = "linear";
```

## Values

This is an open enum. Unrecognized values will be captured as the `Unrecognized<string>` branded type.

```typescript
"linear" | "slerp" | Unrecognized<string>
```