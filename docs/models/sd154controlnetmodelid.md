# Sd154ControlnetModelId

⚠️ NOTE: ControlNet model_ids must be unique. Additionally, they must be compatible with the selected base model.

## Example Usage

```typescript
import { Sd154ControlnetModelId } from "daydream-sdk/models";

let value: Sd154ControlnetModelId =
  "daydreamlive/TemporalNet2-stable-diffusion-v1-5";
```

## Values

This is an open enum. Unrecognized values will be captured as the `Unrecognized<string>` branded type.

```typescript
"lllyasviel/control_v11f1p_sd15_depth" | "lllyasviel/control_v11f1e_sd15_tile" | "lllyasviel/control_v11p_sd15_canny" | "daydreamlive/TemporalNet2-stable-diffusion-v1-5" | Unrecognized<string>
```