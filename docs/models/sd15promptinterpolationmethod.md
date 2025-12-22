# Sd15PromptInterpolationMethod

Method for interpolating between multiple prompts. Slerp provides smoother transitions than linear.

## Example Usage

```typescript
import { Sd15PromptInterpolationMethod } from "daydream-sdk/models";

let value: Sd15PromptInterpolationMethod = "slerp";
```

## Values

```typescript
"linear" | "slerp"
```