# Sdxl2PromptInterpolationMethod

Method for interpolating between multiple prompts. Slerp provides smoother transitions than linear.

## Example Usage

```typescript
import { Sdxl2PromptInterpolationMethod } from "daydream-sdk/models";

let value: Sdxl2PromptInterpolationMethod = "linear";
```

## Values

```typescript
"linear" | "slerp"
```