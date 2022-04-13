# vue3imagelocation

How to reference images in Vue 3



> vue3imagelocation@0.0.0 build 
> vue-tsc --noEmit && vite build

vite v2.9.1 building for production...
✓ 9 modules transformed.
[vite]: Rollup failed to resolve import "/subfolder/images/img_pub.webp" from "src/components/ShowImages.vue".
This is most likely unintended because it can break your application at runtime.
If you do want to externalize this module explicitly add it to
`build.rollupOptions.external`
error during build:
Error: [vite]: Rollup failed to resolve import "/subfolder/images/img_pub.webp" from "src/components/ShowImages.vue".
This is most likely unintended because it can break your application at runtime.
If you do want to externalize this module explicitly add it to
`build.rollupOptions.external`
    at onRollupWarning (D:\GitHub\pubic\vue3imagelocation\node_modules\vite\dist\node\chunks\dep-611778e0.js:39103:19)
    at onwarn (D:\GitHub\pubic\vue3imagelocation\node_modules\vite\dist\node\chunks\dep-611778e0.js:38919:13)
    at Object.onwarn (D:\GitHub\pubic\vue3imagelocation\node_modules\rollup\dist\shared\rollup.js:23129:13)
    at ModuleLoader.handleResolveId (D:\GitHub\pubic\vue3imagelocation\node_modules\rollup\dist\shared\rollup.js:22419:26)        
    at D:\GitHub\pubic\vue3imagelocation\node_modules\rollup\dist\shared\rollup.js:22380:26
The terminal process "C:\WINDOWS\System32\WindowsPowerShell\v1.0\powershell.exe -Command npm run build" terminated with exit code: 1.

Terminal will be reused by tasks, press any key to close it.
