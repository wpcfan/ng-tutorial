# 适合于 Angular 开发的 devcontainer 配置

这是一个适合于 Angular 开发的 devcontainer 配置，可以在 vscode 中使用 devcontainer 插件直接启动一个开发环境。 已经包含 `Angular CLI` 和 `JSON Server` 等常用工具和服务。

## 使用方法

1. 安装 vscode 插件：Remote - Containers
2. 使用 Github 的模板功能，创建一个新的仓库，即在本仓库的右上角点击 `Use this template`，然后在新仓库中 clone 代码。
3. 打开 vscode，打开项目根目录
4. 点击左下角的 `><` 图标，选择 `Reopen in Container`

## 配置说明

- `Dockerfile`：用于构建 devcontainer 的 Dockerfile
- `devcontainer.json`：devcontainer 配置文件
- `docker-compose.yml`：用于启动数据库等服务

## 服务说明

- `nodejs`：nodejs 环境
- `typescript`：typescript 编译环境

## 运行端口

- `4000`：Angular 服务

## 注意事项

- 请确保安装了 Docker Desktop
- 请确保安装了 vscode 插件：Remote - Containers
- 请避免端口冲突，如有冲突请修改 `docker-compose.yml` 中的端口映射，本项目默认暴露端口为 `4000`
