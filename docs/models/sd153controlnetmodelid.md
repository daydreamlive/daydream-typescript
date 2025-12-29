# Sd153ControlnetModelId

⚠️ NOTE: ControlNet model_ids must be unique. Additionally, they must be compatible with the selected base model.

## Example Usage

```typescript
import { Sd153ControlnetModelId } from "@daydreamlive/sdk/models";

let value: Sd153ControlnetModelId = "lllyasviel/control_v11p_sd15_canny";
```

## Values

This is an open enum. Unrecognized values will be captured as the `Unrecognized<string>` branded type.

```typescript
"lllyasviel/control_v11f1p_sd15_depth" | "lllyasviel/control_v11f1e_sd15_tile" | "lllyasviel/control_v11p_sd15_canny" | "daydreamlive/TemporalNet2-stable-diffusion-v1-5" | Unrecognized<string>
```