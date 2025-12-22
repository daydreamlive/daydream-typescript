# Sdxl3IpAdapter

IP adapter — Turns on IP-Adapter style conditioning and is fully hot-swappable. Available for SDXL, SDXL-faceid, SD1.5

## Example Usage

```typescript
import { Sdxl3IpAdapter } from "daydream-sdk/models";

let value: Sdxl3IpAdapter = {};
```

## Fields

| Field                                                                                                                                      | Type                                                                                                                                       | Required                                                                                                                                   | Description                                                                                                                                |
| ------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------ |
| `type`                                                                                                                                     | [models.Sdxl3IpAdapterType](../models/sdxl3ipadaptertype.md)                                                                               | :heavy_minus_sign:                                                                                                                         | Type of IP adapter. Use 'faceid' for SDXL-faceid models, 'regular' for others                                                              |
| `enabled`                                                                                                                                  | *boolean*                                                                                                                                  | :heavy_minus_sign:                                                                                                                         | Whether IP adapter is enabled                                                                                                              |
| `scale`                                                                                                                                    | *number*                                                                                                                                   | :heavy_minus_sign:                                                                                                                         | Strength of IP adapter style conditioning                                                                                                  |
| `weightType`                                                                                                                               | [models.Sdxl3WeightType](../models/sdxl3weighttype.md)                                                                                     | :heavy_minus_sign:                                                                                                                         | Weight interpolation method for IP adapter style conditioning. Controls how the style influence changes throughout the generation process. |