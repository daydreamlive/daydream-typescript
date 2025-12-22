# SDTurboPromptInterpolationMethod

Method for interpolating between multiple prompts. Slerp provides smoother transitions than linear.

## Example Usage

```typescript
import { SDTurboPromptInterpolationMethod } from "daydream-sdk/models";

let value: SDTurboPromptInterpolationMethod = "slerp";
```

## Values

```typescript
"linear" | "slerp"
```