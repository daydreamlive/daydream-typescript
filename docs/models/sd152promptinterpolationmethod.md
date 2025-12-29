# Sd152PromptInterpolationMethod

Method for interpolating between multiple prompts. Slerp provides smoother transitions than linear.

## Example Usage

```typescript
import { Sd152PromptInterpolationMethod } from "@daydreamlive/sdk/models";

let value: Sd152PromptInterpolationMethod = "slerp";
```

## Values

```typescript
"linear" | "slerp"
```