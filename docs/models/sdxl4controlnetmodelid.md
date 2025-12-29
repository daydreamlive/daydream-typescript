# Sdxl4ControlnetModelId

⚠️ NOTE: ControlNet model_ids must be unique. Additionally, they must be compatible with the selected base model.

## Example Usage

```typescript
import { Sdxl4ControlnetModelId } from "@daydreamlive/sdk/models";

let value: Sdxl4ControlnetModelId = "xinsir/controlnet-depth-sdxl-1.0";
```

## Values

This is an open enum. Unrecognized values will be captured as the `Unrecognized<string>` branded type.

```typescript
"xinsir/controlnet-depth-sdxl-1.0" | "xinsir/controlnet-canny-sdxl-1.0" | "xinsir/controlnet-tile-sdxl-1.0" | Unrecognized<string>
```