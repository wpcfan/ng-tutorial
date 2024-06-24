# 项目设置和基础构建

## 设置 Angular 开发环境

### 使用我们提供的 CodeSpace

我们提供了一个 CodeSpace 环境，你可以直接使用这个环境来开发 Angular 应用。你可以通过以下步骤来使用 CodeSpace 环境：

1. 打开 [CodeSpace](https://github.com/codespaces/glowing-enigma-pjpqxq4jxcrwg9)
2. 点击 `Code` 按钮，然后选择 `Open with Codespaces` 选项
3. 等待一段时间，直到 CodeSpace 环境启动完成
4. 在 CodeSpace 环境中，打开终端，然后运行 `ng serve` 命令来启动开发服务器

### 本地安装

首先，你需要确保开发环境中安装了以下工具：

1. Node.js: Angular 需要 Node.js 的当期活跃版本或者长期支持版本（LTS），在目前 angular 18.0.0 版本中，Node.js 的最低版本要求是 20.0.0 （当期活跃版本）或 18.0.0 （长期支持版本）。
2. npm 包管理器: Angular CLI 依赖于 npm 包管理器，所以你需要确保安装了 npm 包管理器。你可以通过运行 `npm -v` 命令来检查 npm 包管理器是否安装。
3. Angular CLI: Angular CLI 是一个命令行工具，用于创建、构建和维护 Angular 应用。你可以通过运行 `ng --version` 命令来检查 Angular CLI 是否安装。
4. 编辑器: 你可以使用任何编辑器来开发 Angular 应用，但是推荐使用 Visual Studio Code 编辑器。Visual Studio Code 是一个轻量级的编辑器，支持 TypeScript 和 Angular 开发。
5. 浏览器: Angular 应用是基于 Web 技术的，所以你需要一个现代浏览器来运行 Angular 应用。推荐使用 Chrome 或 Edge 浏览器，因为有官方维护的开发者工具。

#### 创建 Angular 应用

在安装了 Node.js 和 Angular CLI 之后，你可以通过以下步骤来创建一个 Angular 应用：

1. 打开终端或者命令行工具
2. 运行 `ng new <your-app-name> --directory .` 命令来创建一个 Angular 应用，其中 `<your-app-name>` 是你的应用名称，`--directory .` 参数表示在当前目录下创建应用。
3. 进入到 `my-app` 目录，运行 `ng serve` 命令来启动开发服务器

### 熟悉 Angular CLI 命令

Angular CLI 是一个命令行工具，用于创建、构建和维护 Angular 应用。你可以通过以下命令来创建、构建和运行 Angular 应用：

1. 创建一个新的 Angular 应用：`ng new <your-app-name>` 可以创建一个新的 Angular 项目，默认是在当前目录下创建项目，也就是在当前目录下新建一个名为 `<your-app-name>` 的文件夹。我们的项目由于是希望在根目录下创建项目，所以使用了 `--directory .` 参数。
