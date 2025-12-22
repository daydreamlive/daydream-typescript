# Sd154WeightType

Weight interpolation method for IP adapter style conditioning. Controls how the style influence changes throughout the generation process.

## Example Usage

```typescript
import { Sd154WeightType } from "daydream-sdk/models";

let value: Sd154WeightType = "strong style transfer";
```

## Values

This is an open enum. Unrecognized values will be captured as the `Unrecognized<string>` branded type.

```typescript
"linear" | "ease in" | "ease out" | "ease in-out" | "reverse in-out" | "weak input" | "weak output" | "weak middle" | "strong middle" | "style transfer" | "composition" | "strong style transfer" | "style and composition" | "style transfer precise" | "composition precise" | Unrecognized<string>
```