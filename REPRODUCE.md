# REPRODUCE

```bash
$ pnpm run build

> basic@ build C:\Users\REDACTED\ghq\github.com\mika-sandbox\honox-ssg-invalid-island-components
> vite build --config vite.config.a.ts --mode client && vite build --config vite.config.a.ts

vite v5.2.11 building for client...
✓ 26 modules transformed.
dist/.vite/manifest.json         0.94 kB │ gzip: 0.28 kB
dist/static/counter-6pBdz0j3.js  0.22 kB │ gzip: 0.19 kB
dist/static/runtime-HRCq6XW0.js  2.17 kB │ gzip: 1.06 kB
dist/static/client-EZewls-e.js   9.18 kB │ gzip: 4.18 kB
✓ built in 165ms
vite v5.2.11 building for production...
✓ 1 modules transformed.
rendering chunks (1)...19:30:04 [vite] Error when evaluating SSR module ./app/server.ts:
|- TypeError: (intermediate value).glob is not a function
    at Module.createApp (file:///C:/Users/REDACTED/ghq/github.com/mika-sandbox/honox-ssg-invalid-island-components/node_modules/.pnpm/honox@0.1.18_hono@4.3.11/node_modules/honox/dist/server/with-defaults.js:8:50)
    at eval (C:/Users/REDACTED/ghq/github.com/mika-sandbox/honox-ssg-invalid-island-components/app/server.ts:7:35)
    at async instantiateModule (file:///C:/Users/REDACTED/ghq/github.com/mika-sandbox/honox-ssg-invalid-island-components/node_modules/.pnpm/vite@5.2.11/node_modules/vite/dist/node/chunks/dep-cNe07EU9.js:55058:9)

x Build failed in 93ms
error during build:
TypeError: (intermediate value).glob is not a function
    at Module.createApp (file:///C:/Users/REDACTED/ghq/github.com/mika-sandbox/honox-ssg-invalid-island-components/node_modules/.pnpm/honox@0.1.18_hono@4.3.11/node_modules/honox/dist/server/with-defaults.js:8:50)
    at eval (C:/Users/REDACTED/ghq/github.com/mika-sandbox/honox-ssg-invalid-island-components/app/server.ts:7:35)
    at async instantiateModule (file:///C:/Users/REDACTED/ghq/github.com/mika-sandbox/honox-ssg-invalid-island-components/node_modules/.pnpm/vite@5.2.11/node_modules/vite/dist/node/chunks/dep-cNe07EU9.js:55058:9)
 ELIFECYCLE  Command failed with exit code 1.```