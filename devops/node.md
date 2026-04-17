# env
- fnm
- pnpm
# note
fnm管理node版本，pnpm替代npm，pnpm dlx替代npx
```
npm config set cache "D:\npm-cache](D:\user\AppData\Local\npm-cache"

```

```
PS C:\Users\deads> pnpm config list
@jsr:registry=https://npm.jsr.io/
cache=D:\user\AppData\Local\npm-cache
cache-dir=D:\user\AppData\Local\pnpm\cache
global-bin-dir=D:\user\AppData\Local\pnpm\bin
global-dir=D:\user\AppData\Local\pnpm\global
globalconfig=C:\Users\deads\AppData\Local\pnpm\config\rc
https-proxy=http://127.0.0.1:7897
npm-globalconfig=D:\user\AppData\Local\pnpm\etc\npmrc
proxy=http://127.0.0.1:7897
registry=https://registry.npmjs.org/
state-dir=D:\user\AppData\Local\pnpm\state
store-dir=D:\user\AppData\Local\pnpm\store
user-agent=pnpm/10.30.3 npm/? node/v20.11.1 win32 x64
```

```
PS C:\Users\deads> npm config list
; "global" config from C:\Users\deads\AppData\Local\fnm_multishells\12140_1776319281046\etc\npmrc

; cache = "D:\\user\\AppData\\Local\\npm-cache" ; overridden by user

; "user" config from C:\Users\deads\.npmrc

cache = "D:\\user\\AppData\\Local\\npm-cache"
https-proxy = "http://127.0.0.1:7897"
proxy = "http://127.0.0.1:7897"

; node bin location = C:\Users\deads\AppData\Local\fnm_multishells\12140_1776319281046\node.exe
; node version = v25.8.0
; npm local prefix = C:\Users\deads
; npm version = 11.11.0
; cwd = C:\Users\deads
; HOME = C:\Users\deads
; Run `npm config ls -l` to show all defaults.
```