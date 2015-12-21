On 
 - ``` Windows 7 ```
 - ``` PowerShell 2.0 ```
 - ``` node 4.2.0 ```
 - ``` npm 3.5.2 ```
 

running:

``` npm run coverage ```

yields:

```
PS {path to my home dir}\dev\projects\nyc-ava-demo> npm run coverage

> nyc-ava-demo@0.1.0 coverage {path to my home dir}\dev\projects\nyc-ava-demo
> nyc npm test

module.js:339
    throw err;
    ^

Error: Cannot find module '{path to my home dir}\dev\projects\nyc-ava-demo\npm'
    at Function.Module._resolveFilename (module.js:337:15)
    at Function.Module._load (module.js:287:25)
    at Function.Module.runMain (module.js:467:10)
    at Function.runMain ({path to my home dir}\.node-spawn-wrap-10936-a578ddb5e7e6\node:40:10)
    at Object.<anonymous> ({path to my home dir}\dev\projects\nyc-ava-demo\node_modules\nyc\bin\nyc.js:17:6)
    at Module._compile (module.js:435:26)
    at Object.Module._extensions..js (module.js:442:10)
    at Module.load (module.js:356:32)
    at Function.Module._load (module.js:311:12)
    at Function.Module.runMain (module.js:467:10)
----------|----------|----------|----------|----------|----------------|
File      |  % Stmts | % Branch |  % Funcs |  % Lines |Uncovered Lines |
----------|----------|----------|----------|----------|----------------|
----------|----------|----------|----------|----------|----------------|
All files |      100 |      100 |      100 |      100 |                |
----------|----------|----------|----------|----------|----------------|


npm ERR! Windows_NT 6.1.7601
npm ERR! argv "C:\\Program Files\\nodejs\\node.exe" "C:\\Program Files\\nodejs\\node_modules\\npm\\bin\\npm-cli.js" "run" "coverage"
npm ERR! node v4.2.0
npm ERR! npm  v3.5.2
npm ERR! code ELIFECYCLE
npm ERR! nyc-ava-demo@0.1.0 coverage: `nyc npm test`
npm ERR! Exit status 1
npm ERR!
npm ERR! Failed at the nyc-ava-demo@0.1.0 coverage script 'nyc npm test'.
npm ERR! Make sure you have the latest version of node.js and npm installed.
npm ERR! If you do, this is most likely a problem with the nyc-ava-demo package,
npm ERR! not with npm itself.
npm ERR! Tell the author that this fails on your system:
npm ERR!     nyc npm test
npm ERR! You can get information on how to open an issue for this project with:
npm ERR!     npm bugs nyc-ava-demo
npm ERR! Or if that isn't available, you can get their info via:
npm ERR!     npm owner ls nyc-ava-demo
npm ERR! There is likely additional logging output above.

npm ERR! Please include the following file with any support request:
npm ERR!     {path to my home dir}\dev\projects\nyc-ava-demo\npm-debug.log
```
