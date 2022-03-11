- [文档](https://www.electronjs.org/zh/docs/latest/tutorial/quick-start#prerequisites)

```
1. 按照文档创建完文件后

2. npm install --save-dev @electron-forge/cli

3. npx electron-forge import 之后报错Error: Could not find module with name: @electron-forge/maker-squirrel. Make sure it's listed in the devDependencies of your package.json

解决办法：[1111](https://stackoverflow.com/questions/67616975/npm-run-make-is-not-working-in-electron-forge)

输入命令：npm install --save-dev @electron-forge/maker-squirrel@6.0.0-beta.33

我猜可能是这个插件不是最新的

4. npm run make 

```