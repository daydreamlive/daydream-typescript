# Sdxl1IpAdapterType

Type of IP adapter. Use 'faceid' for SDXL-faceid models, 'regular' for others

## Example Usage

```typescript
import { Sdxl1IpAdapterType } from "daydream-sdk/models";

let value: Sdxl1IpAdapterType = "regular";
```

## Values

This is an open enum. Unrecognized values will be captured as the `Unrecognized<string>` branded type.

```typescript
"regular" | "faceid" | Unrecognized<string>
```