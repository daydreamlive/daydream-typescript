# PromptInterpolationMethod

Method for interpolating between multiple prompts. Slerp provides smoother transitions than linear.

## Example Usage

```typescript
import { PromptInterpolationMethod } from "daydream-sdk/models/operations";

let value: PromptInterpolationMethod = "slerp";
```

## Values

```typescript
"linear" | "slerp"
```