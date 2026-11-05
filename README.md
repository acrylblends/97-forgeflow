# ForgeFlow

A software factory cockpit turning a product specification into a coordinated, reviewable build pipeline.

An ACRYL Blends blueprint for the **Software Factories** category (`acrylblends.forgeflow`, category 97 of 100).

Status: designed, being built. `design/spec.md` is the specification and `design/mockup.html` the mockup (open it in a browser). The app itself,
composed from Cordis plugins (one `plugins/<feature>/` folder and one `blend.yaml` row per feature), lands here when it passes review.

When it is ready you will start it with:

```sh
npm create acrylblends@latest my-app -- --from acrylblends.forgeflow
cd my-app && npm install && npm run dev
```

Listed on https://acrylblends.github.io/blends and https://acryl.dev/blends.
