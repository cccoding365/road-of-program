# Package.json

## package.json 的常见配置

```json
{
  "name": "parcel-experiment",
  "version": "1.0.0",
  "description": "A simple npm package to learn about using npm",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "Chris Mills",
  "license": "ISC"
}
```

### ✨ 必须属性

- name - 名称

A name to identify the app. Just press `Return` to accept the default parcel-experiment.

- version - 版本

The starting version number for the app. Again, just press `Return` to accept the default 1.0.0.

### 🎨 描述信息

- description - 描述信息

A quick description of the app's purpose. Type in something really simple, like "A simple npm package to learn about using npm", then press `Return` .

- keywords - 关键词

The keywords of the project.

- author - 作者

The author of the project. Type your own name, and press `Return` .

- contributors - 贡献者

The contributors of the project.

- homepage - 主页

The homepage of the project.

- repository - 仓库

The repository of the project.

- bugs - Bug 反馈地址

### 💫 依赖配置

- dependencies - 生产环境依赖
- devDependencies - 开发环境依赖
- peerDependencies - 兼容依赖
- optionalDependencies - 不阻断依赖
- bundledDependencies - 打包依赖
- engines - 版本要求

### 🏹 脚本配置

- script 
- config

### 📮 文件&目录

- main - 程序入口

This will be the top-level JavaScript file of the app. The default index.js is fine for now — press `Return` .

- browser - 程序入口
- module - 程序入口
- bin - 命令行工具入口
- files - 发布文件配置
- man - man 文档
- directories - 项目目录

### 🎄 发布配置

- private - 限制发布
- preferGlobal - 警告本地安装
- publishConfig - 限制发布仓库和版本
- os - 限制用户安装系统
- cpu - 限制用户安装 CPU
- license - 开源协议

The license to publish the package under. Press `Return` to accept the default for now.


### 🎍 第三方配置

- typings
- eslintConfig
- babel
- unpkg
- lint-staged
- gitHooks
- browserlist

etc