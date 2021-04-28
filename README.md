## webstorm-paths-bug
This is a minimal repository to reproduce a bug in Webstorm v2021.1.<br/>
When using the Typescript paths option in tsconfig.json code analysis is broken.<br/>

## Steps to reproduce
1. Clone repository<br/>
2. Open project my-project in Webstorm 2021.1
3. Open the file shared/shared-code.ts
4. Code analysis is broken for the function isString() imported from the library meta-validator<br/>
Please see attached screenshot.

![screenshot](https://raw.githubusercontent.com/rmuchall/webstorm-paths-bug/master/screenshot.png)
