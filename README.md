# Error

    ❯ ember s
    WARNING: Node v18.18.2 is not tested against Ember CLI on your platform. We recommend that you use the most-recent "Active LTS" version of Node.js. See https://git.io/v7S5n for details.
    Building into /tmp/embroider/de794a
    ⠋ building... [@embroider/webpack]assets by status 2.27 MiB [big]
      asset chunk.d5e9898aa41d44bcf6bd.js 1.62 MiB [emitted] [immutable] [big] (id hint: vendors)
      asset chunk.288b7d188df0e7d71b6c.js 661 KiB [emitted] [immutable] [big] (id hint: vendors)
    asset chunk.535e31ee71cd4c8ccecc.js 141 KiB [emitted] [immutable]
    asset chunk.92494643946caed0a35c.js 38.9 KiB [emitted] [immutable] (name: assets/test.js)
    asset chunk.e15e74d1f5072526d6f8.js 7.5 KiB [emitted] [immutable] (name: assets/ember-app-issue-ember-data.js)
    Entrypoint assets/ember-app-issue-ember-data.js [big] 1.77 MiB = chunk.d5e9898aa41d44bcf6bd.js 1.62 MiB chunk.535e31ee71cd4c8ccecc.js 141 KiB chunk.e15e74d1f5072526d6f8.js 7.5 KiB
    Entrypoint assets/test.js [big] 2.44 MiB = chunk.d5e9898aa41d44bcf6bd.js 1.62 MiB chunk.288b7d188df0e7d71b6c.js 661 KiB chunk.535e31ee71cd4c8ccecc.js 141 KiB chunk.92494643946caed0a35c.js 38.9 KiB
    runtime modules 6.83 KiB 13 modules
    modules by path ./node_modules/.pnpm/ 1.25 MiB 244 modules
    modules by path ../ 291 KiB 47 modules
    modules by path ./initializers/*.js 2.41 KiB 5 modules
    modules by path ./helpers/*.js 1.53 KiB 5 modules
    modules by path ./services/*.js 590 bytes 4 modules
    modules by path ./transforms/*.js 895 bytes 4 modules
    modules by path ./*.js 1.37 KiB 3 modules
    modules by path ./serializers/*.js 607 bytes 3 modules
    modules by path ./assets/*.js 59.9 KiB 2 modules
    modules by path ./tests/ 662 bytes 2 modules
    + 7 modules

    ERROR in ./node_modules/.pnpm/@ember-data+adapter@4.11.3_@ember-data+store@4.11.3_@ember+string@3.1.1_ember-inflector@4.0.2_webpack@5.89.0/node_modules/@ember-data/adapter/-private/build-url-mixin.js 2:0-41
    Module not found: Error: Can't resolve '@ember/string' in '$TMPDIR/embroider/de794a/node_modules/.pnpm/@ember-data+adapter@4.11.3_@ember-data+store@4.11.3_@ember+string@3.1.1_ember-inflector@4.0.2_webpack@5.89.0/node_modules/@ember-data/adapter/-private'
    @ ./assets/ember-app-issue-ember-data.js 181:9-208

    ERROR in ./node_modules/.pnpm/@ember-data+adapter@4.11.3_@ember-data+store@4.11.3_@ember+string@3.1.1_ember-inflector@4.0.2_webpack@5.89.0/node_modules/@ember-data/adapter/json-api.js 5:0-42
    Module not found: Error: Can't resolve '@ember/string' in '$TMPDIR/embroider/de794a/node_modules/.pnpm/@ember-data+adapter@4.11.3_@ember-data+store@4.11.3_@ember+string@3.1.1_ember-inflector@4.0.2_webpack@5.89.0/node_modules/@ember-data/adapter'
    @ ./assets/ember-app-issue-ember-data.js 214:9-192

    ERROR in ./node_modules/.pnpm/@ember-data+debug@4.11.3_@ember+string@3.1.1_webpack@5.89.0/node_modules/@ember-data/debug/index.js 31:0-55
    Module not found: Error: Can't resolve '@ember/string' in '$TMPDIR/embroider/de794a/node_modules/.pnpm/@ember-data+debug@4.11.3_@ember+string@3.1.1_webpack@5.89.0/node_modules/@ember-data/debug'
    @ ./assets/ember-app-issue-ember-data.js 220:9-138

    ERROR in ./node_modules/.pnpm/@ember-data+model@4.11.3_@babel+core@7.23.3_@ember-data+record-data@4.11.3_@ember-data+store@_3i2zazxo6snzhtnrbf4kzngyra/node_modules/@ember-data/model/-private/belongs-to.js 3:0-42
    Module not found: Error: Can't resolve '@ember/string' in '$TMPDIR/embroider/de794a/node_modules/.pnpm/@ember-data+model@4.11.3_@babel+core@7.23.3_@ember-data+record-data@4.11.3_@ember-data+store@_3i2zazxo6snzhtnrbf4kzngyra/node_modules/@ember-data/model/-private'
    @ ./assets/ember-app-issue-ember-data.js 232:9-213

    ERROR in ./node_modules/.pnpm/@ember-data+model@4.11.3_@babel+core@7.23.3_@ember-data+record-data@4.11.3_@ember-data+store@_3i2zazxo6snzhtnrbf4kzngyra/node_modules/@ember-data/model/-private/has-many.js 7:0-42
    Module not found: Error: Can't resolve '@ember/string' in '$TMPDIR/embroider/de794a/node_modules/.pnpm/@ember-data+model@4.11.3_@babel+core@7.23.3_@ember-data+record-data@4.11.3_@ember-data+store@_3i2zazxo6snzhtnrbf4kzngyra/node_modules/@ember-data/model/-private'
    @ ./assets/ember-app-issue-ember-data.js 247:9-211

    ERROR in ./node_modules/.pnpm/@ember-data+model@4.11.3_@babel+core@7.23.3_@ember-data+record-data@4.11.3_@ember-data+store@_3i2zazxo6snzhtnrbf4kzngyra/node_modules/@ember-data/model/-private/relationship-meta.js 1:0-42
    Module not found: Error: Can't resolve '@ember/string' in '$TMPDIR/embroider/de794a/node_modules/.pnpm/@ember-data+model@4.11.3_@babel+core@7.23.3_@ember-data+record-data@4.11.3_@ember-data+store@_3i2zazxo6snzhtnrbf4kzngyra/node_modules/@ember-data/model/-private'
    @ ./assets/ember-app-issue-ember-data.js 292:9-220

    ERROR in ./node_modules/.pnpm/@ember-data+serializer@4.11.3_@ember-data+store@4.11.3_@ember+string@3.1.1_ember-inflector@4.0.2_webpack@5.89.0/node_modules/@ember-data/serializer/-private/embedded-records-mixin.js 4:0-41
    Module not found: Error: Can't resolve '@ember/string' in '$TMPDIR/embroider/de794a/node_modules/.pnpm/@ember-data+serializer@4.11.3_@ember-data+store@4.11.3_@ember+string@3.1.1_ember-inflector@4.0.2_webpack@5.89.0/node_modules/@ember-data/serializer/-private'
    @ ./assets/ember-app-issue-ember-data.js 358:9-221

    ERROR in ./node_modules/.pnpm/@ember-data+serializer@4.11.3_@ember-data+store@4.11.3_@ember+string@3.1.1_ember-inflector@4.0.2_webpack@5.89.0/node_modules/@ember-data/serializer/json-api.js 5:0-42
    Module not found: Error: Can't resolve '@ember/string' in '$TMPDIR/embroider/de794a/node_modules/.pnpm/@ember-data+serializer@4.11.3_@ember-data+store@4.11.3_@ember+string@3.1.1_ember-inflector@4.0.2_webpack@5.89.0/node_modules/@ember-data/serializer'
    @ ./assets/ember-app-issue-ember-data.js 382:9-198

    ERROR in ./node_modules/.pnpm/@ember-data+serializer@4.11.3_@ember-data+store@4.11.3_@ember+string@3.1.1_ember-inflector@4.0.2_webpack@5.89.0/node_modules/@ember-data/serializer/json.js 6:0-42
    Module not found: Error: Can't resolve '@ember/string' in '$TMPDIR/embroider/de794a/node_modules/.pnpm/@ember-data+serializer@4.11.3_@ember-data+store@4.11.3_@ember+string@3.1.1_ember-inflector@4.0.2_webpack@5.89.0/node_modules/@ember-data/serializer'
    @ ./assets/ember-app-issue-ember-data.js 385:9-194

    ERROR in ./node_modules/.pnpm/@ember-data+serializer@4.11.3_@ember-data+store@4.11.3_@ember+string@3.1.1_ember-inflector@4.0.2_webpack@5.89.0/node_modules/@ember-data/serializer/rest.js 5:0-52
    Module not found: Error: Can't resolve '@ember/string' in '$TMPDIR/embroider/de794a/node_modules/.pnpm/@ember-data+serializer@4.11.3_@ember-data+store@4.11.3_@ember+string@3.1.1_ember-inflector@4.0.2_webpack@5.89.0/node_modules/@ember-data/serializer'
    @ ./assets/ember-app-issue-ember-data.js 388:9-194

    ERROR in ./node_modules/.pnpm/@ember-data+store@4.11.3_@babel+core@7.23.3_@ember-data+model@4.11.3_@ember-data+record-data@_4gcfvvmx4bdnawnbuhqmwrl7r4/node_modules/@ember-data/store/-private/utils/normalize-model-name.js 1:0-42
    Module not found: Error: Can't resolve '@ember/string' in '$TMPDIR/embroider/de794a/node_modules/.pnpm/@ember-data+store@4.11.3_@babel+core@7.23.3_@ember-data+model@4.11.3_@ember-data+record-data@_4gcfvvmx4bdnawnbuhqmwrl7r4/node_modules/@ember-data/store/-private/utils'
    @ ./assets/ember-app-issue-ember-data.js 469:9-229

    11 errors have detailed information that is not shown.
    Use 'stats.errorDetails: true' resp. '--stats-error-details' to show it.

    webpack 5.89.0 compiled with 11 errors in 4802 ms
    Build Error (PackagerRunner) in node_modules/.pnpm/@ember-data+adapter@4.11.3_@ember-data+store@4.11.3_@ember+string@3.1.1_ember-inflector@4.0.2_webpack@5.89.0/node_modules/@ember-data/adapter/-private/build-url-mixin.js

    Module not found: Error: Can't resolve '@ember/string' in '$TMPDIR/embroider/de794a/node_modules/.pnpm/@ember-data+adapter@4.11.3_@ember-data+store@4.11.3_@ember+string@3.1.1_ember-inflector@4.0.2_webpack@5.89.0/node_modules/@ember-data/adapter/-private/build-url-mixin.js'


    Stack Trace and Error Report: /tmp/error.dump.1ea6d6790e24ffe95f296b344440620b.log
    cleaning up...

# Log

    =================================================================================

    ENV Summary:

      TIME: Tue Nov 14 2023 19:54:40 GMT+0300 (Moscow Standard Time)
      TITLE: ember
      ARGV:
      - /home/lolmaus/.volta/tools/image/node/18.18.2/bin/node
      - /home/lolmaus/Code/mainmatter/mainmatter/ember-app-issue-ember-data/node_modules/ember-cli/bin/ember
      - s
      EXEC_PATH: /home/lolmaus/.volta/tools/image/node/18.18.2/bin/node
      TMPDIR: /tmp
      SHELL: /bin/bash
      PATH:
      - /home/lolmaus/.volta/tools/image/yarn/1.22.10/bin
      - /home/lolmaus/.volta/tools/image/node/18.18.2/bin
      - /home/lolmaus/.cargo/bin
      - /home/lolmaus/.volta/bin
      - /home/lolmaus/.volta/bin
      - /usr/local/sbin
      - /usr/local/bin
      - /usr/sbin
      - /usr/bin
      - /sbin
      - /bin
      - /usr/games
      - /usr/local/games
      - /usr/lib/wsl/lib
      - /mnt/c/Program Files/Volta/
      - /mnt/c/program files/python3/scripts/
      - /mnt/c/program files/python3/
      - /mnt/c/windows/system32
      - /mnt/c/windows
      - /mnt/c/windows/system32/wbem
      - /mnt/c/windows/system32/windowspowershell/v1.0/
      - /mnt/c/users/lolmaus/appdata/roaming/nvm
      - /mnt/c/windows/system32/openssh/
      - /mnt/c/users/lolmaus/appdata/local/microsoft/windowsapps
      - /mnt/c/program files/oracle/virtualbox
      - /mnt/c/portable apps/sysinternalssuite
      - /mnt/c/portable apps/nirsoft_package_enc_1.20.39/nirsoft
      - /mnt/c/program files/docker toolbox
      - /mnt/c/users/lolmaus/appda
      - /mnt/c/program files/git/cmd
      - /mnt/c/Program Files (x86)/NVIDIA Corporation/PhysX/Common
      - /mnt/c/ProgramData/chocolatey/bin
      - /mnt/c/Program Files/nodejs/
      - /mnt/c/WINDOWS/system32
      - /mnt/c/WINDOWS
      - /mnt/c/WINDOWS/System32/Wbem
      - /mnt/c/WINDOWS/System32/WindowsPowerShell/v1.0/
      - /mnt/c/WINDOWS/System32/OpenSSH/
      - /mnt/c/Program Files/Intel/WiFi/bin/
      - /mnt/c/Program Files/Common Files/Intel/WirelessCommon/
      - /mnt/c/Program Files (x86)/Kensington/TrackballWorks
      - /mnt/c/Program Files (x86)/Yarn/bin/
      - /mnt/c/Program Files/Calibre2/
      - /mnt/c/Program Files/CMake/bin
      - /mnt/c/Program Files/Zero Install
      - /mnt/c/WINDOWS/system32
      - /mnt/c/WINDOWS
      - /mnt/c/WINDOWS/System32/Wbem
      - /mnt/c/WINDOWS/System32/WindowsPowerShell/v1.0/
      - /mnt/c/WINDOWS/System32/OpenSSH/
      - /mnt/c/Program Files/Intel/Intel(R) Memory and Storage Tool/
      - /mnt/c/Program Files/dotnet/
      - /mnt/c/Program Files (x86)/FAHClient
      - /mnt/c/Program Files/NVIDIA Corporation/NVIDIA NvDLISR
      - /mnt/c/Program Files/Docker/Docker/resources/bin
      - /mnt/c/Program Files/Mullvad VPN/resources
      - /mnt/c/Program Files/WireGuard/
      - /mnt/c/Program Files/Git/cmd
      - /mnt/c/Program Files/PowerShell/7/
      - /mnt/c/Users/lolmaus/scoop/shims
      - /mnt/c/Users/lolmaus/AppData/Local/Volta/bin
      - /mnt/c/Users/lolmaus/AppData/Local/Microsoft/WindowsApps
      - /mnt/c/Program Files/Microsoft VS Code/bin
      - /mnt/c/Program Files/Oracle/VirtualBox
      - /mnt/c/Users/lolmaus/AppData/Roaming/nvm
      - /mnt/c/Program Files/nodejs
      - /mnt/c/Portable Apps/SysinternalsSuite
      - /mnt/c/Portable Apps/nirsoft_package_enc_1.20.39/NirSoft
      - /mnt/c/Program Files/Microsoft VS Code Insiders/bin
      - /mnt/c/Users/lolmaus/AppData/Local/Programs/Microsoft VS Code Insiders/bin
      - /mnt/c/Users/lolmaus/AppData/Local/Programs/Microsoft VS Code/bin
      - /mnt/c/Users/lolmaus/AppData/Roaming/npm
      - /mnt/c/Program Files/Intel/WiFi/bin/
      - /mnt/c/Program Files/Common Files/Intel/WirelessCommon/
      - /mnt/c/Users/lolmaus/AppData/Local/GitHubDesktop/bin
      - /mnt/c/Users/lolmaus/AppData/Local/Yarn/bin
      - /mnt/c/Program Files (x86)/Notepad++
      - /mnt/c/Program Files (x86)/FAHClient
      - /mnt/c/Users/lolmaus/AppData/Local/Microsoft/WindowsApps
      - /mnt/c/Program Files (x86)/GitHub CLI/
      - /mnt/c/Program Files/JetBrains/IntelliJ IDEA 2020.3.3/bin
      - /mnt/c/Program Files (x86)/BrowserStackLocal/
      - /mnt/c/Program Files/JetBrains/WebStorm 221.4501.160/bin
      - /mnt/c/Program Files/JetBrains/IntelliJ IDEA 2022.1.2/bin
      - /mnt/c/Users/lolmaus/AppData/Local/JetBrains/Toolbox/scripts
      - /snap/bin
      - /home/lolmaus/.local/bin
      - /home/lolmaus/.local/bin
      PLATFORM: linux x64
      FREEMEM: 23312453632
      TOTALMEM: 33632305152
      UPTIME: 31027.23
      LOADAVG: 3.01,1.65,1.37
      CPUS:
      - AMD Ryzen 7 2700X Eight-Core Processor - 3700
      - AMD Ryzen 7 2700X Eight-Core Processor - 3700
      - AMD Ryzen 7 2700X Eight-Core Processor - 3700
      - AMD Ryzen 7 2700X Eight-Core Processor - 3700
      - AMD Ryzen 7 2700X Eight-Core Processor - 3700
      - AMD Ryzen 7 2700X Eight-Core Processor - 3700
      - AMD Ryzen 7 2700X Eight-Core Processor - 3700
      - AMD Ryzen 7 2700X Eight-Core Processor - 3700
      - AMD Ryzen 7 2700X Eight-Core Processor - 3700
      - AMD Ryzen 7 2700X Eight-Core Processor - 3700
      - AMD Ryzen 7 2700X Eight-Core Processor - 3700
      - AMD Ryzen 7 2700X Eight-Core Processor - 3700
      - AMD Ryzen 7 2700X Eight-Core Processor - 3700
      - AMD Ryzen 7 2700X Eight-Core Processor - 3700
      - AMD Ryzen 7 2700X Eight-Core Processor - 3700
      - AMD Ryzen 7 2700X Eight-Core Processor - 3700
      ENDIANNESS: LE
      VERSIONS:
      - acorn: 8.10.0
      - ada: 2.6.0
      - ares: 1.19.1
      - brotli: 1.0.9
      - cldr: 43.1
      - icu: 73.2
      - llhttp: 6.0.11
      - modules: 108
      - napi: 9
      - nghttp2: 1.57.0
      - nghttp3: 0.7.0
      - ngtcp2: 0.8.1
      - node: 18.18.2
      - openssl: 3.0.10+quic
      - simdutf: 3.2.14
      - tz: 2023c
      - undici: 5.26.3
      - unicode: 15.0
      - uv: 1.44.2
      - uvwasi: 0.0.18
      - v8: 10.2.154.26-node.26
      - zlib: 1.2.13.1-motley

    ERROR Summary:

      - broccoliBuilderErrorStack: ModuleNotFoundError: Module not found: Error: Can't resolve '@ember/string' in '$TMPDIR/embroider/de794a/node_modules/.pnpm/@ember-data+adapter@4.11.3_@ember-data+store@4.11.3_@ember+string@3.1.1_ember-inflector@4.0.2_webpack@5.89.0/node_modules/@ember-data/adapter/-private/build-url-mixin.js'
        at /home/lolmaus/Code/mainmatter/mainmatter/ember-app-issue-ember-data/node_modules/.pnpm/webpack@5.89.0/node_modules/webpack/lib/Compilation.js:2022:28
        at /home/lolmaus/Code/mainmatter/mainmatter/ember-app-issue-ember-data/node_modules/.pnpm/webpack@5.89.0/node_modules/webpack/lib/NormalModuleFactory.js:817:13
        at eval (eval at create (/home/lolmaus/Code/mainmatter/mainmatter/ember-app-issue-ember-data/node_modules/.pnpm/tapable@2.2.1/node_modules/tapable/lib/HookCodeFactory.js:33:10), <anonymous>:10:1)
        at /home/lolmaus/Code/mainmatter/mainmatter/ember-app-issue-ember-data/node_modules/.pnpm/webpack@5.89.0/node_modules/webpack/lib/NormalModuleFactory.js:275:22
        at eval (eval at create (/home/lolmaus/Code/mainmatter/mainmatter/ember-app-issue-ember-data/node_modules/.pnpm/tapable@2.2.1/node_modules/tapable/lib/HookCodeFactory.js:33:10), <anonymous>:9:1)
        at /home/lolmaus/Code/mainmatter/mainmatter/ember-app-issue-ember-data/node_modules/.pnpm/webpack@5.89.0/node_modules/webpack/lib/NormalModuleFactory.js:448:22
        at /home/lolmaus/Code/mainmatter/mainmatter/ember-app-issue-ember-data/node_modules/.pnpm/webpack@5.89.0/node_modules/webpack/lib/NormalModuleFactory.js:118:11
        at /home/lolmaus/Code/mainmatter/mainmatter/ember-app-issue-ember-data/node_modules/.pnpm/webpack@5.89.0/node_modules/webpack/lib/NormalModuleFactory.js:689:25
        at /home/lolmaus/Code/mainmatter/mainmatter/ember-app-issue-ember-data/node_modules/.pnpm/webpack@5.89.0/node_modules/webpack/lib/NormalModuleFactory.js:893:8
        at /home/lolmaus/Code/mainmatter/mainmatter/ember-app-issue-ember-data/node_modules/.pnpm/webpack@5.89.0/node_modules/webpack/lib/NormalModuleFactory.js:1013:5
      - code: [undefined]
      - codeFrame: Module not found: Error: Can't resolve '@ember/string' in '$TMPDIR/embroider/de794a/node_modules/.pnpm/@ember-data+adapter@4.11.3_@ember-data+store@4.11.3_@ember+string@3.1.1_ember-inflector@4.0.2_webpack@5.89.0/node_modules/@ember-data/adapter/-private/build-url-mixin.js'
      - errorMessage: node_modules/.pnpm/@ember-data+adapter@4.11.3_@ember-data+store@4.11.3_@ember+string@3.1.1_ember-inflector@4.0.2_webpack@5.89.0/node_modules/@ember-data/adapter/-private/build-url-mixin.js: Module not found: Error: Can't resolve '@ember/string' in '$TMPDIR/embroider/de794a/node_modules/.pnpm/@ember-data+adapter@4.11.3_@ember-data+store@4.11.3_@ember+string@3.1.1_ember-inflector@4.0.2_webpack@5.89.0/node_modules/@ember-data/adapter/-private/build-url-mixin.js'
            at PackagerRunner (@embroider/webpack)
      - errorType: Build Error
      - location:
        - column: [undefined]
        - file: node_modules/.pnpm/@ember-data+adapter@4.11.3_@ember-data+store@4.11.3_@ember+string@3.1.1_ember-inflector@4.0.2_webpack@5.89.0/node_modules/@ember-data/adapter/-private/build-url-mixin.js
        - line: [null]
        - treeDir: [undefined]
      - message: node_modules/.pnpm/@ember-data+adapter@4.11.3_@ember-data+store@4.11.3_@ember+string@3.1.1_ember-inflector@4.0.2_webpack@5.89.0/node_modules/@ember-data/adapter/-private/build-url-mixin.js: Module not found: Error: Can't resolve '@ember/string' in '$TMPDIR/embroider/de794a/node_modules/.pnpm/@ember-data+adapter@4.11.3_@ember-data+store@4.11.3_@ember+string@3.1.1_ember-inflector@4.0.2_webpack@5.89.0/node_modules/@ember-data/adapter/-private/build-url-mixin.js'
            at PackagerRunner (@embroider/webpack)
      - name: Error
      - nodeAnnotation: @embroider/webpack
      - nodeName: PackagerRunner
      - originalErrorMessage: Module not found: Error: Can't resolve '@ember/string' in '$TMPDIR/embroider/de794a/node_modules/.pnpm/@ember-data+adapter@4.11.3_@ember-data+store@4.11.3_@ember+string@3.1.1_ember-inflector@4.0.2_webpack@5.89.0/node_modules/@ember-data/adapter/-private/build-url-mixin.js'
      - stack: ModuleNotFoundError: Module not found: Error: Can't resolve '@ember/string' in '$TMPDIR/embroider/de794a/node_modules/.pnpm/@ember-data+adapter@4.11.3_@ember-data+store@4.11.3_@ember+string@3.1.1_ember-inflector@4.0.2_webpack@5.89.0/node_modules/@ember-data/adapter/-private/build-url-mixin.js'
        at /home/lolmaus/Code/mainmatter/mainmatter/ember-app-issue-ember-data/node_modules/.pnpm/webpack@5.89.0/node_modules/webpack/lib/Compilation.js:2022:28
        at /home/lolmaus/Code/mainmatter/mainmatter/ember-app-issue-ember-data/node_modules/.pnpm/webpack@5.89.0/node_modules/webpack/lib/NormalModuleFactory.js:817:13
        at eval (eval at create (/home/lolmaus/Code/mainmatter/mainmatter/ember-app-issue-ember-data/node_modules/.pnpm/tapable@2.2.1/node_modules/tapable/lib/HookCodeFactory.js:33:10), <anonymous>:10:1)
        at /home/lolmaus/Code/mainmatter/mainmatter/ember-app-issue-ember-data/node_modules/.pnpm/webpack@5.89.0/node_modules/webpack/lib/NormalModuleFactory.js:275:22
        at eval (eval at create (/home/lolmaus/Code/mainmatter/mainmatter/ember-app-issue-ember-data/node_modules/.pnpm/tapable@2.2.1/node_modules/tapable/lib/HookCodeFactory.js:33:10), <anonymous>:9:1)
        at /home/lolmaus/Code/mainmatter/mainmatter/ember-app-issue-ember-data/node_modules/.pnpm/webpack@5.89.0/node_modules/webpack/lib/NormalModuleFactory.js:448:22
        at /home/lolmaus/Code/mainmatter/mainmatter/ember-app-issue-ember-data/node_modules/.pnpm/webpack@5.89.0/node_modules/webpack/lib/NormalModuleFactory.js:118:11
        at /home/lolmaus/Code/mainmatter/mainmatter/ember-app-issue-ember-data/node_modules/.pnpm/webpack@5.89.0/node_modules/webpack/lib/NormalModuleFactory.js:689:25
        at /home/lolmaus/Code/mainmatter/mainmatter/ember-app-issue-ember-data/node_modules/.pnpm/webpack@5.89.0/node_modules/webpack/lib/NormalModuleFactory.js:893:8
        at /home/lolmaus/Code/mainmatter/mainmatter/ember-app-issue-ember-data/node_modules/.pnpm/webpack@5.89.0/node_modules/webpack/lib/NormalModuleFactory.js:1013:5

    =================================================================================
