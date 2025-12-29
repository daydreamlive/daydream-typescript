# SDTurbo4ControlnetModelId

⚠️ NOTE: ControlNet model_ids must be unique. Additionally, they must be compatible with the selected base model.

## Example Usage

```typescript
import { SDTurbo4ControlnetModelId } from "@daydreamlive/sdk/models";

let value: SDTurbo4ControlnetModelId =
  "thibaud/controlnet-sd21-color-diffusers";
```

## Values

This is an open enum. Unrecognized values will be captured as the `Unrecognized<string>` branded type.

```typescript
"thibaud/controlnet-sd21-openpose-diffusers" | "thibaud/controlnet-sd21-hed-diffusers" | "thibaud/controlnet-sd21-canny-diffusers" | "thibaud/controlnet-sd21-depth-diffusers" | "thibaud/controlnet-sd21-color-diffusers" | "daydreamlive/TemporalNet2-stable-diffusion-2-1" | Unrecognized<string>
```