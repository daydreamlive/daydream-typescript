<!-- Start SDK Example Usage [usage] -->
```typescript
import { Daydream } from "daydream-sdk";

const daydream = new Daydream({
  bearer: process.env["DAYDREAM_BEARER"] ?? "",
});

async function run() {
  const result = await daydream.streams.create({
    pipeline: "streamdiffusion",
    params: {
      modelId: "stabilityai/sdxl-turbo",
    },
  });

  console.log(result);
}

run();

```
<!-- End SDK Example Usage [usage] -->