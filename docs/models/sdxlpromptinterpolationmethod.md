# SDXLPromptInterpolationMethod

Method for interpolating between multiple prompts. Slerp provides smoother transitions than linear.

## Example Usage

```typescript
import { SDXLPromptInterpolationMethod } from "daydream-sdk/models";

let value: SDXLPromptInterpolationMethod = "slerp";
```

## Values

```typescript
"linear" | "slerp"
```