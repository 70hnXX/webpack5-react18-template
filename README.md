webpack 配置参考[【前端工程化】webpack5 从零搭建完整的 react18+ts 开发和打包环境](https://juejin.cn/post/7111922283681153038)

代码风格配置参考[【前端工程化】配置 React+ts 项目完整的代码及样式格式和 git 提交规范](https://juejin.cn/post/7101596844181962788#heading-1)

### 需要全局安装的插件

- npm install -g eslint
- npm i serve -g
- npm i commitizen -g

### 需要安装的 vscode 插件

- EditorConfig for VS Code
- Prettier - Code formatter
- ESLint

### 使用 git cz ?

将文件添加进暂存区后,可以使用 git cz 代替 git commit 和 git push

### 打包后启动服务

```
npm i serve -g
serve -s dist
```

### Unknown rule function-calc-no-invalid.Stylelint(function-calc-no-invalid) ?

npm i stylelint-config-standard : 更新 stylelint-config-standard 的版本即可
