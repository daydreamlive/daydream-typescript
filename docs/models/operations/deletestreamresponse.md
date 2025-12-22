# DeleteStreamResponse

Default Response

## Example Usage

```typescript
import { DeleteStreamResponse } from "daydream-sdk/models/operations";

let value: DeleteStreamResponse = {
  success: false,
  data: {},
};
```

## Fields

| Field                                              | Type                                               | Required                                           | Description                                        |
| -------------------------------------------------- | -------------------------------------------------- | -------------------------------------------------- | -------------------------------------------------- |
| `success`                                          | *boolean*                                          | :heavy_check_mark:                                 | Whether the stream deletion was successful         |
| `data`                                             | [operations.Data](../../models/operations/data.md) | :heavy_check_mark:                                 | Empty object confirming successful deletion        |