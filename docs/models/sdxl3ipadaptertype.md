# Sdxl3IpAdapterType

Type of IP adapter. Use 'faceid' for SDXL-faceid models, 'regular' for others

## Example Usage

```typescript
import { Sdxl3IpAdapterType } from "@daydreamlive/sdk/models";

let value: Sdxl3IpAdapterType = "regular";
```

## Values

This is an open enum. Unrecognized values will be captured as the `Unrecognized<string>` branded type.

```typescript
"regular" | "faceid" | Unrecognized<string>
```