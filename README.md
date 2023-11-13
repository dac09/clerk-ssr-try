# README

## To run locally:

1. `yarn install`
2. `yarn rw dev`


## To run on gitpod
Click this link -> https://gitpod.io/new/#https://github.com/dac09/clerk-ssr-try

Navigate to localhost:8910 and you will see:


> Note: you do not need to configure the env vars `CLERK_PUBLISHABLE_KEY` and `CLERK_SECRET_KEY`,
> because the error actually happens before any of the Clerk related code is run!


```
/Users/dac09/Experiments/clerk-ssr-try/node_modules/@clerk/clerk-react/dist/esm/index.js:1
import "./chunk-3W5G4CYI.js";
^^^^^^

SyntaxError: Cannot use import statement outside a module
    at internalCompileFunction (node:internal/vm:73:18)
    at wrapSafe (node:internal/modules/cjs/loader:1178:20)
    at Module._compile (node:internal/modules/cjs/loader:1220:27)
    at Module._extensions..js (node:internal/modules/cjs/loader:1310:10)
    at Module.load (node:internal/modules/cjs/loader:1119:32)
    at Module._load (node:internal/modules/cjs/loader:960:12)
    at ModuleWrap.<anonymous> (node:internal/modules/esm/translators:169:29)
    at ModuleJob.run (node:internal/modules/esm/module_job:194:25)
```
