## 주의 사항

- npm만 사용 pnpm이나 yarn에서는 빌드 오류 발생

<br>

## 설치 버전

```ps
entry-hw on  master [!?] is 📦 v1.9.41 via  v16.20.0 took 1m1s
❯ python --version
Python 3.10.9

entry-hw on  master [!?] is 📦 v1.9.41 via  v16.20.0
❯ node --version
v16.20.0

entry-hw on  master [!?] is 📦 v1.9.41 via  v16.20.0
❯ npm --version
9.6.6

entry-hw on  master [!?] is 📦 v1.9.41 via  v16.20.0
❯ yarn --version
1.22.19
```

<br>

## npm install

```ps
entry-hw on  master is 📦 v1.9.41 via  v16.20.0
❯ npm install
npm WARN deprecated chokidar@2.1.8: Chokidar 2 does not receive security updates since 2019. Upgrade to chokidar 3 with 15x fewer dependencies

up to date, audited 1190 packages in 23s

54 packages are looking for funding
  run `npm fund` for details

54 vulnerabilities (16 moderate, 22 high, 16 critical)

To address issues that do not require attention, run:
  npm audit fix

To address all issues possible (including breaking changes), run:
  npm audit fix --force

Some issues need review, and may require choosing
a different dependency.

Run `npm audit` for details.
```

<br>

## npm run setting

```ps
entry-hw on  master [!?] is 📦 v1.9.41 via  v16.20.0 took 24s
❯ npm run setting

> entry-hw@1.9.41 setting
> npm run rebuild && npm run webpack:dev


> entry-hw@1.9.41 rebuild
> electron-rebuild -f -w serialport,node-hid

⠴ Building module: bindings, Completed: 0gyp info find Python using Python version 3.10.9 found at "C:\Users\realwolf\AppData\Local\Programs\Python\Python310\python.exe"
⠼ Building module: bindings, Completed: 0gyp info find VS using VS2019 (16.11.33529.622) found at:
gyp info find VS "C:\Program Files (x86)\Microsoft Visual Studio\2019\BuildTools"
gyp info find VS run with --verbose for detailed information
(node:19664) [DEP0150] DeprecationWarning: Setting process.config is deprecated. In the future the property will be read-only.
(Use `node --trace-deprecation ...` to show where the warning was created)
gyp info spawn C:\Users\realwolf\AppData\Local\Programs\Python\Python310\python.exe
gyp info spawn args [
gyp info spawn args   'D:\\project\\entry\\entry-hw\\node_modules\\node-gyp\\gyp\\gyp_main.py',
gyp info spawn args   'binding.gyp',
gyp info spawn args   '-f',
gyp info spawn args   'msvs',
gyp info spawn args   '-I',
gyp info spawn args   'D:\\project\\entry\\entry-hw\\node_modules\\@serialport\\bindings\\build\\config.gypi',
gyp info spawn args   '-I',
gyp info spawn args   'D:\\project\\entry\\entry-hw\\node_modules\\node-gyp\\addon.gypi',
gyp info spawn args   '-I',
gyp info spawn args   'C:\\Users\\realwolf\\.electron-gyp\\12.0.2\\include\\node\\common.gypi',
gyp info spawn args   '-Dlibrary=shared_library',
gyp info spawn args   '-Dvisibility=default',
gyp info spawn args   '-Dnode_root_dir=C:\\Users\\realwolf\\.electron-gyp\\12.0.2',
gyp info spawn args   '-Dnode_gyp_dir=D:\\project\\entry\\entry-hw\\node_modules\\node-gyp',
gyp info spawn args   '-Dnode_lib_file=C:\\\\Users\\\\realwolf\\\\.electron-gyp\\\\12.0.2\\\\<(target_arch)\\\\node.lib',
gyp info spawn args   '-Dmodule_root_dir=D:\\project\\entry\\entry-hw\\node_modules\\@serialport\\bindings',
gyp info spawn args   '-Dnode_engine=v8',
gyp info spawn args   '--depth=.',
gyp info spawn args   '--no-parallel',
gyp info spawn args   '--generator-output',
gyp info spawn args   'D:\\project\\entry\\entry-hw\\node_modules\\@serialport\\bindings\\build',
gyp info spawn args   '-Goutput_dir=.'
gyp info spawn args ]
⠹ Building module: bindings, Completed: 0gyp info spawn C:\Program Files (x86)\Microsoft Visual Studio\2019\BuildTools\MSBuild\Current\Bin\MSBuild.exe
gyp info spawn args [
gyp info spawn args   'build/binding.sln',
gyp info spawn args   '/clp:Verbosity=minimal',
gyp info spawn args   '/nologo',
gyp info spawn args   '/p:Configuration=Release;Platform=x64',
gyp info spawn args   map: [Function (anonymous)]
gyp info spawn args ]
⠸ Building module: bindings, Completed: 0이 솔루션의 프로젝트를 한 번에 하나씩 빌드합니다. 병렬 빌드를 사용하려면 "-m"
스위치를 추가하세요.
⠧ Building module: bindings, Completed: 0  serialport.cpp
⠸ Building module: bindings, Completed: 0C:\Users\realwolf\.electron-gyp\12.0.2\include\node\v8.h(1650,55): warning C4996: 'v8::Module::ResolveCallback': Use Re
solveModuleCallback [D:\project\entry\entry-hw\node_modules\@serialport\bindings\build\bindings.vcxproj]
⠼ Building module: bindings, Completed: 0C:\Users\realwolf\.electron-gyp\12.0.2\include\node\v8-platform.h(1,1): warning C4819: 현재 코드 페이지(949)에서 표시할 수 없는 문자가 파일
에 들어 있습니다. 데이터가 손실되지 않게 하려면 해당 파일을 유니코드 형식으로 저장하십시오. [D:\project\entry\entry-hw\node_modules\@serialport\bindings\build
\bindings.vcxproj]
C:\Users\realwolf\.electron-gyp\12.0.2\include\node\node.h(658,1): warning C4819: 현재 코드 페이지(949)에서 표시할 수 없는 문자가 파일에 들어
있습니다. 데이터가 손실되지 않게 하려면 해당 파일을 유니코드 형식으로 저장하십시오. [D:\project\entry\entry-hw\node_modules\@serialport\bindings\build\bind
ings.vcxproj]
⠙ Building module: bindings, Completed: 0  serialport_win.cpp
⠧ Building module: bindings, Completed: 0C:\Users\realwolf\.electron-gyp\12.0.2\include\node\v8.h(1650,55): warning C4996: 'v8::Module::ResolveCallback': Use Re
solveModuleCallback [D:\project\entry\entry-hw\node_modules\@serialport\bindings\build\bindings.vcxproj]
C:\Users\realwolf\.electron-gyp\12.0.2\include\node\v8-platform.h(1,1): warning C4819: 현재 코드 페이지(949)에서 표시할 수 없는 문자가 파일
에 들어 있습니다. 데이터가 손실되지 않게 하려면 해당 파일을 유니코드 형식으로 저장하십시오. [D:\project\entry\entry-hw\node_modules\@serialport\bindings\build
\bindings.vcxproj]
⠇ Building module: bindings, Completed: 0C:\Users\realwolf\.electron-gyp\12.0.2\include\node\node.h(658,1): warning C4819: 현재 코드 페이지(949)에서 표시할 수 없는 문자가 파일에 들어
있습니다. 데이터가 손실되지 않게 하려면 해당 파일을 유니코드 형식으로 저장하십시오. [D:\project\entry\entry-hw\node_modules\@serialport\bindings\build\bind
ings.vcxproj]
⠙ Building module: bindings, Completed: 0  win_delay_load_hook.cc
⠦ Building module: bindings, Completed: 0     D:\project\entry\entry-hw\node_modules\@serialport\bindings\build\Release\bindings.lib 라이브러리 및 D:\project\entry\en
  try-hw\node_modules\@serialport\bindings\build\Release\bindings.exp 개체를 생성하고 있습니다.
  코드를 생성하고 있습니다.
  Previous IPDB not found, fall back to full compilation.
⠇ Building module: bindings, Completed: 0  All 479 functions were compiled because no usable IPDB/IOBJ from previous compilation was found.
  코드를 생성했습니다.
⠋ Building module: bindings, Completed: 0  bindings.vcxproj -> D:\project\entry\entry-hw\node_modules\@serialport\bindings\build\Release\\bindings.node
⠏ Building module: node-hid, Completed: 1gyp info find Python using Python version 3.10.9 found at "C:\Users\realwolf\AppData\Local\Programs\Python\Python310\python.exe"
⠸ Building module: node-hid, Completed: 1gyp info find VS using VS2019 (16.11.33529.622) found at:
gyp info find VS "C:\Program Files (x86)\Microsoft Visual Studio\2019\BuildTools"
gyp info find VS run with --verbose for detailed information
gyp info spawn C:\Users\realwolf\AppData\Local\Programs\Python\Python310\python.exe
gyp info spawn args [
gyp info spawn args   'D:\\project\\entry\\entry-hw\\node_modules\\node-gyp\\gyp\\gyp_main.py',
gyp info spawn args   'binding.gyp',
gyp info spawn args   '-f',
gyp info spawn args   'msvs',
gyp info spawn args   '-I',
gyp info spawn args   'D:\\project\\entry\\entry-hw\\node_modules\\node-hid\\build\\config.gypi',
gyp info spawn args   '-I',
gyp info spawn args   'D:\\project\\entry\\entry-hw\\node_modules\\node-gyp\\addon.gypi',
gyp info spawn args   '-I',
gyp info spawn args   'C:\\Users\\realwolf\\.electron-gyp\\12.0.2\\include\\node\\common.gypi',
gyp info spawn args   '-Dlibrary=shared_library',
gyp info spawn args   '-Dvisibility=default',
gyp info spawn args   '-Dnode_root_dir=C:\\Users\\realwolf\\.electron-gyp\\12.0.2',
gyp info spawn args   '-Dnode_gyp_dir=D:\\project\\entry\\entry-hw\\node_modules\\node-gyp',
gyp info spawn args   '-Dnode_lib_file=C:\\\\Users\\\\realwolf\\\\.electron-gyp\\\\12.0.2\\\\<(target_arch)\\\\node.lib',
gyp info spawn args   '-Dmodule_root_dir=D:\\project\\entry\\entry-hw\\node_modules\\node-hid',
gyp info spawn args   '-Dnode_engine=v8',
gyp info spawn args   '--depth=.',
gyp info spawn args   '--no-parallel',
gyp info spawn args   '--generator-output',
gyp info spawn args   'D:\\project\\entry\\entry-hw\\node_modules\\node-hid\\build',
gyp info spawn args   '-Goutput_dir=.'
gyp info spawn args ]
⠏ Building module: node-hid, Completed: 1gyp info spawn C:\Program Files (x86)\Microsoft Visual Studio\2019\BuildTools\MSBuild\Current\Bin\MSBuild.exe
gyp info spawn args [
gyp info spawn args   'build/binding.sln',
gyp info spawn args   '/clp:Verbosity=minimal',
gyp info spawn args   '/nologo',
gyp info spawn args   '/p:Configuration=Release;Platform=x64',
gyp info spawn args   map: [Function (anonymous)]
gyp info spawn args ]
⠋ Building module: node-hid, Completed: 1이 솔루션의 프로젝트를 한 번에 하나씩 빌드합니다. 병렬 빌드를 사용하려면 "-m"
스위치를 추가하세요.
⠸ Building module: node-hid, Completed: 1  hid.c
⠇ Building module: node-hid, Completed: 1  win_delay_load_hook.cc
⠹ Building module: node-hid, Completed: 1  hidapi.vcxproj -> D:\project\entry\entry-hw\node_modules\node-hid\build\Release\\hidapi.lib
⠸ Building module: node-hid, Completed: 1  HID.cc
⠋ Building module: node-hid, Completed: 1  win_delay_load_hook.cc
⠼ Building module: node-hid, Completed: 1     D:\project\entry\entry-hw\node_modules\node-hid\build\Release\HID.lib 라이브러리 및 D:\project\entry\entry-hw\node_modul
  es\node-hid\build\Release\HID.exp 개체를 생성하고 있습니다.
⠴ Building module: node-hid, Completed: 1  코드를 생성하고 있습니다.
  Previous IPDB not found, fall back to full compilation.
⠇ Building module: node-hid, Completed: 1  All 859 functions were compiled because no usable IPDB/IOBJ from previous compilation was found.
  코드를 생성했습니다.
⠹ Building module: node-hid, Completed: 1  HID.vcxproj -> D:\project\entry\entry-hw\node_modules\node-hid\build\Release\\HID.node
✔ Rebuild Complete

> entry-hw@1.9.41 webpack:dev
> cross-env NODE_ENV=development webpack

Hash: 91800a5b1d2855dc9d42a412d23aed4d27ae620b8b8a02029c3a074803e36c138b96b3c7a779fd6c
Version: webpack 4.43.0
Child mainRouter:
    Hash: 91800a5b1d2855dc9d42
    Time: 24902ms
    Built at: 2023. 05. 06. 오후 10:37:34
                      Asset      Size  Chunks                   Chunk Names
        mainRouter.build.js  2.31 MiB    main  [emitted]        main
    mainRouter.build.js.map  2.65 MiB    main  [emitted] [dev]  main
    Entrypoint main = mainRouter.build.js mainRouter.build.js.map
    [./app/src/common/constants.ts] 2.07 KiB {main} [built]
    [./app/src/main/core/dataHandler.ts] 2.06 KiB {main} [built]
    [./app/src/main/core/directoryPaths.ts] 692 bytes {main} [built]
    [./app/src/main/core/functions/downloadModule.ts] 9.96 KiB {main} [built]
    [./app/src/main/core/hardwareListManager.ts] 9.97 KiB {main} [built]
    [./app/src/main/core/ipcMainManager.ts] 1.84 KiB {main} [built]
    [./app/src/main/core/rendererConsole.ts] 1.63 KiB {main} [built]
    [./app/src/main/core/scannerManager.ts] 1.31 KiB {main} [built]
    [./app/src/main/core/serial/flasher.ts] 9.04 KiB {main} [built]
    [./app/src/main/electron/functions/createLogger.ts] 1.72 KiB {main} [built]
    [./app/src/main/electron/modifyValidator.ts] 3.09 KiB {main} [built]
    [./app/src/main/mainRouter.ts] 29.9 KiB {main} [built]
    [./nativeNodeRequire.js] external "./nativeNodeRequire.js" 42 bytes {main} [built]
    [electron] external "electron" 42 bytes {main} [built]
    [path] external "path" 42 bytes {main} [built]
        + 470 hidden modules
Child
    Hash: a412d23aed4d27ae620b
    Time: 20760ms
    Built at: 2023. 05. 06. 오후 10:37:30
                    Asset      Size  Chunks                   Chunk Names
        preload.bundle.js  1.62 MiB    main  [emitted]        main
    preload.bundle.js.map  1.84 MiB    main  [emitted] [dev]  main
    Entrypoint main = preload.bundle.js preload.bundle.js.map
    [./app/src/common/constants.ts] 2.07 KiB {main} [built]
    [./app/src/preload/bleProcessManager.ts] 13.2 KiB {main} [built]
    [./app/src/preload/index.ts] 1.28 KiB {main} [built]
    [./app/src/preload/ipcRendererManager.ts] 4.27 KiB {main} [built]
    [./app/src/preload/lang sync recursive ^\.\/.*\.js$] ./app/src/preload/lang sync ^\.\/.*\.js$ 196 bytes {main} [optional] [built]
    [./app/src/preload/lang/en.js] 481 KiB {main} [built]
    [./app/src/preload/lang/jp.js] 574 KiB {main} [optional] [built]
    [./app/src/preload/lang/ko.js] 555 KiB {main} [optional] [built]
    [./app/src/preload/rendererRouter.ts] 13.7 KiB {main} [built]
    [./app/src/preload/translations.json] 7.97 KiB {main} [built]
    [./app/src/preload/translator.ts] 1.25 KiB {main} [built]
    [electron] external "electron" 42 bytes {main} [built]
Child
    Hash: 8b8a02029c3a074803e3
    Time: 23386ms
    Built at: 2023. 05. 06. 오후 10:37:33
                                              Asset       Size  Chunks                   Chunk Names
                                     about.build.js   1.08 MiB   about  [emitted]        about
                                 about.build.js.map   1.24 MiB   about  [emitted] [dev]  about
                                      main.build.js   1.93 MiB    main  [emitted]        main
                                  main.build.js.map   2.17 MiB    main  [emitted] [dev]  main
     resources/014aae810636a4eb52c05e6d24f1dfc5.png  778 bytes          [emitted]
     resources/197d57aaa98226ec57a1a39cad9051bf.png  668 bytes          [emitted]
     resources/1aaafe24417101edd67b628c46b17d1f.png  268 bytes          [emitted]
     resources/1dae6441fe97ee4616f1e07a99fb812e.png   1.52 KiB          [emitted]
     resources/204f94dedb2663010c5f446ff414c239.png  858 bytes          [emitted]
     resources/32a6ad194e0d88511317c0ad27e95ae9.png  507 bytes          [emitted]
     resources/3d1c34b1031a787e841fbe7f9800fd39.png  629 bytes          [emitted]
     resources/57d16524c8a4fa27360e1211cb705f69.svg  637 bytes          [emitted]
     resources/5a262e2f7c69c3158e3c48388f99feca.png   2.64 KiB          [emitted]
     resources/6943c29703f840e114abf616dad60aa5.png  430 bytes          [emitted]
     resources/6f9583bf2bdfc1da16f5ff299d24035d.png  509 bytes          [emitted]
     resources/86b677afdb0554404e9187492bd1ecb9.png   1.06 KiB          [emitted]
     resources/89ec6ac3a5fb49b81a03e9cdad7bf5a9.png  241 bytes          [emitted]
     resources/9b75b237e463bcd92594e26123b6013a.svg  852 bytes          [emitted]
    resources/9f44950eb918193ef1ebd2b3366cab17.woff    983 KiB          [emitted]
     resources/b1ff3bf482b442cf90a893bca8de03e4.png  442 bytes          [emitted]
     resources/b2f29a2417c6ccf759a81d9e2964e1db.png   1.76 KiB          [emitted]
     resources/bb73a67f2c3623cfe8b512f0a1445fae.png   1.62 KiB          [emitted]
     resources/e3776dc73db6bf09774e119a92ad4679.svg  834 bytes          [emitted]
     resources/e806bd802e2d3418653d3b28b7fe9685.png   2.87 KiB          [emitted]
     resources/ec91de08c985e013da6ccb77dc7e69e4.png  223 bytes          [emitted]
     resources/efc56dd2d7b50d1894cfd5fa2e30c908.png  998 bytes          [emitted]
    Entrypoint main = main.build.js main.build.js.map
    Entrypoint about = about.build.js about.build.js.map
    [./app/src/common/constants.ts] 2.07 KiB {main} [built]
    [./app/src/renderer/fonts/NanumGothic.woff] 88 bytes {main} {about} [built]
    [./app/src/renderer/images/about/fill-1.png] 87 bytes {about} [built]
    [./app/src/renderer/images/about/logo.png] 87 bytes {about} [built]
    [./app/src/renderer/images/logo.png] 87 bytes {main} [built]
    [./app/src/renderer/react/about/App.tsx] 704 bytes {about} [built]
    [./app/src/renderer/react/about/GlobalStyle.ts] 1.47 KiB {about} [built]
    [./app/src/renderer/react/main/App.tsx] 1.59 KiB {main} [built]
    [./app/src/renderer/react/main/GlobalStyle.ts] 3.37 KiB {main} [built]
    [./app/src/renderer/react/main/constants/constants.ts] 1.77 KiB {main} [built]
    [./app/src/renderer/react/main/functions/makeConsoleAsciiArt.ts] 2.24 KiB {main} [built]
    [./app/src/renderer/react/main/hooks/usePreload.ts] 474 bytes {main} [built]
    [./app/src/renderer/react/main/store/index.ts] 814 bytes {main} [built]
    [./app/src/renderer/react/main/store/middlewares/entryHardwareMiddleware.ts] 11 KiB {main} [built]
    [./app/src/renderer/react/main/store/modules/common.ts] 4.5 KiB {main} [built]
        + 111 hidden modules
Child
    Hash: 6c138b96b3c7a779fd6c
    Time: 6587ms
    Built at: 2023. 05. 06. 오후 10:37:41
                  Asset      Size  Chunks                   Chunk Names
        index.bundle.js  44.5 KiB    main  [emitted]        main
    index.bundle.js.map  47.8 KiB    main  [emitted] [dev]  main
    Entrypoint main = index.bundle.js index.bundle.js.map
    [../mainRouter.build] external "./main/mainRouter.build" 42 bytes {main} [built]
    [./app/src/main/electron/commonUtils.ts] 1.52 KiB {main} [built]
    [./app/src/main/electron/electronDirectoryPaths.ts] 1.94 KiB {main} [built]
    [./app/src/main/electron/functions/checkUpdate.ts] 2.12 KiB {main} [built]
    [./app/src/main/electron/functions/configInitialize.ts] 2.77 KiB {main} [built]
    [./app/src/main/electron/functions/createLogger.ts] 1.72 KiB {main} [built]
    [./app/src/main/electron/functions/parseCommandLine.ts] 1.62 KiB {main} [built]
    [./app/src/main/electron/functions/registerGlobalShortcut.ts] 627 bytes {main} [built]
    [./app/src/main/electron/index.ts] 10.2 KiB {main} [built]
    [./app/src/main/electron/serverProcessManager.ts] 4.75 KiB {main} [built]
    [./app/src/main/electron/windowManager.ts] 3.62 KiB {main} [built]
    [./package.json] 3.69 KiB {main} [built]
    [electron] external "electron" 42 bytes {main} [built]
    [fs] external "fs" 42 bytes {main} [built]
    [path] external "path" 42 bytes {main} [built]
        + 5 hidden modules

entry-hw on  master [!?] is 📦 v1.9.41 via  v16.20.0 took 1m1s
❯
```


