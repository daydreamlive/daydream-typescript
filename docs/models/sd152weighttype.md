# Sd152WeightType

Weight interpolation method for IP adapter style conditioning. Controls how the style influence changes throughout the generation process.

## Example Usage

```typescript
import { Sd152WeightType } from "@daydreamlive/sdk/models";

let value: Sd152WeightType = "weak input";
```

## Values

```typescript
"linear" | "ease in" | "ease out" | "ease in-out" | "reverse in-out" | "weak input" | "weak output" | "weak middle" | "strong middle" | "style transfer" | "composition" | "strong style transfer" | "style and composition" | "style transfer precise" | "composition precise"
```