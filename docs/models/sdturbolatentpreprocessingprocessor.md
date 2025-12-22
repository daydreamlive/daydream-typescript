# SDTurboLatentPreprocessingProcessor

## Example Usage

```typescript
import { SDTurboLatentPreprocessingProcessor } from "daydream-sdk/models";

let value: SDTurboLatentPreprocessingProcessor = {
  type: "latent_feedback",
};
```

## Fields

| Field                                                                                | Type                                                                                 | Required                                                                             | Description                                                                          |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
| `type`                                                                               | [models.SDTurboLatentPreprocessingType](../models/sdturbolatentpreprocessingtype.md) | :heavy_check_mark:                                                                   | N/A                                                                                  |
| `enabled`                                                                            | *boolean*                                                                            | :heavy_minus_sign:                                                                   | Whether this processor is active                                                     |
| `params`                                                                             | Record<string, *any*>                                                                | :heavy_minus_sign:                                                                   | N/A                                                                                  |