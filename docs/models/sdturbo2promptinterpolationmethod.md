# SDTurbo2PromptInterpolationMethod

Method for interpolating between multiple prompts. Slerp provides smoother transitions than linear.

## Example Usage

```typescript
import { SDTurbo2PromptInterpolationMethod } from "daydream-sdk/models";

let value: SDTurbo2PromptInterpolationMethod = "linear";
```

## Values

```typescript
"linear" | "slerp"
```