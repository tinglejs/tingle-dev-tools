# tingle-dev-tools

---

这是 tingle 组件开发工具集。独立更新、统一维护。旨在为所有的 tingle 组件开发者提供便捷、一致的开发体验。


## Usage

- 安装、更新本地 tingle 组件项目中的工具集

```
npm install tingle-dev-tools
```

- 修改项目目录中的 `gulpfile.js`

```javascript
var gulp = require('gulp');
var devTools = require('tingle-dev-tools');
gulp.tasks = devTools.tasks;
```

- 开启调试服务器

```
gulp server
```

> 注：`gulp server`、`gulp d`、`gulp develop` 均为本地调试服务器的别名，但建议使用 `gulp server` 因为更好的辨识性。