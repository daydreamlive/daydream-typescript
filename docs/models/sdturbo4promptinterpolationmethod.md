# SDTurbo4PromptInterpolationMethod

Method for interpolating between multiple prompts. Slerp provides smoother transitions than linear.

## Example Usage

```typescript
import { SDTurbo4PromptInterpolationMethod } from "@daydreamlive/sdk/models";

let value: SDTurbo4PromptInterpolationMethod = "slerp";
```

## Values

This is an open enum. Unrecognized values will be captured as the `Unrecognized<string>` branded type.

```typescript
"linear" | "slerp" | Unrecognized<string>
```