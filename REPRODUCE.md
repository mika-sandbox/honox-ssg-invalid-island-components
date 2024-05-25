# REPRODUCE

```bash
 pnpm run build

> basic@ build C:\Users\REDACTED\ghq\github.com\mika-sandbox\honox-ssg-invalid-island-components
> vite build --mode client && vite build

vite v5.2.11 building for client...
✓ 26 modules transformed.
dist/.vite/manifest.json         0.94 kB │ gzip: 0.28 kB
dist/static/counter-6pBdz0j3.js  0.22 kB │ gzip: 0.19 kB
dist/static/runtime-HRCq6XW0.js  2.17 kB │ gzip: 1.06 kB
dist/static/client-EZewls-e.js   9.18 kB │ gzip: 4.18 kB
✓ built in 172ms
vite v5.2.11 building for production...
✓ 1 modules transformed.
x Build failed in 60ms
error during build:
Error: [@hono/vite-ssg] Failed to load url ./src/index.tsx (resolved id: ./src/index.tsx). Does the file exist?
    at loadAndTransform (file:///C:/Users/REDACTED/ghq/github.com/mika-sandbox/honox-ssg-invalid-island-components/node_modules/.pnpm/vite@5.2.11/node_modules/vite/dist/node/chunks/dep-cNe07EU9.js:53884:21)
    at async instantiateModule (file:///C:/Users/REDACTED/ghq/github.com/mika-sandbox/honox-ssg-invalid-island-components/node_modules/.pnpm/vite@5.2.11/node_modules/vite/dist/node/chunks/dep-cNe07EU9.js:54954:10)
 ELIFECYCLE  Command failed with exit code 1.
```