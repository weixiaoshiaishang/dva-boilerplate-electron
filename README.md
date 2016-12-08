# dva-boilerplate-electron

Boilerplate to kickstart creating an app with Electron and [dva](https://github.com/dvajs/dva).

## Getting started

In your directory, run:

```bash
$ curl -fsSL https://github.com/sorrycc/dva-boilerplate-electron/archive/master.tar.gz | tar -xz --strip-components 2
```

You can also `git clone` or [download](https://github.com/sorrycc/dva-boilerplate-electron/archive/master.zip) this repo and get contents of the boilerplate folder.

## Directory Structure

```js
+ dist            // pack 完后的输出，.dmg, .exe, .zip, .app 等文件
+ build           // background.png, icon.icns, icon.ico
+ app             // 用于 pack 给用户的目录
  + dist          // src 目录打包完放这里
  + assets        // 字体、图片等资源文件
  + pages         // 存放页面
  - package.json  // 生产依赖，存 dependencies
+ src             // 源码
  + main          // main
  + renderer      // renderer
  + shared        // main 和 renderer 公用文件
- package.json    // 开发依赖，存 devDependencies
```

## Screenshot

<img src="https://zos.alipayobjects.com/rmsportal/LAARQwsZLSimLnXugGID.png" width="912" height="712" />

## License

[MIT](https://tldrlegal.com/license/mit-license)
