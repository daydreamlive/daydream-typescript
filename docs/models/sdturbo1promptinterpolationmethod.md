# SDTurbo1PromptInterpolationMethod

Method for interpolating between multiple prompts. Slerp provides smoother transitions than linear.

## Example Usage

```typescript
import { SDTurbo1PromptInterpolationMethod } from "@daydreamlive/sdk/models";

let value: SDTurbo1PromptInterpolationMethod = "linear";
```

## Values

This is an open enum. Unrecognized values will be captured as the `Unrecognized<string>` branded type.

```typescript
"linear" | "slerp" | Unrecognized<string>
```