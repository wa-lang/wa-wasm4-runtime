# 凹语言定制的 WASM4 运行时

基于 https://github.com/aduros/wasm4/tree/main/runtimes/web 定制.

变化部分:

- 取消 WASM 文件的 64KB 大小限制

构建测试流程:

1. `npm install` 安装依赖
2. `npm run build:slim` 构建目标, 在 dist 目录
3. 将游戏WASM模块放到 `dist/cart.wasm` 文件
4. 在 dist 目录启动 Web 服务, 打开网页浏览
