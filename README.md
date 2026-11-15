# Folinov Console 发布仓库

工作室内部办公系统的安装包与自动更新分发仓库（仅存放构建产物）。

## 最新版本

- 版本：0.1.1
- 安装包：[releases/FolinovConsole-Setup-0.1.1.exe](releases/FolinovConsole-Setup-0.1.1.exe)
- 更新说明：降低数据库连接占用，修复多人同时在线时第三个人无法连接的问题；登录页新增版本检查与数据库状态提示。

## 下载地址

- 主地址（GitHub 加速）：
  `https://ghproxy.net/https://raw.githubusercontent.com/RainxButterfly/folinov/v0.1.1/releases/FolinovConsole-Setup-0.1.1.exe`
- 镜像地址：
  `https://gh-proxy.com/https://raw.githubusercontent.com/RainxButterfly/folinov/v0.1.1/releases/FolinovConsole-Setup-0.1.1.exe`

## 历史版本

- 0.1.0：[releases/FolinovConsole-Setup-0.1.0.exe](releases/FolinovConsole-Setup-0.1.0.exe)

## 发布新版本

1. 把新的安装包放进 `releases/`，文件名保持 `FolinovConsole-Setup-<版本>.exe`。
2. 提交并打 tag（例如 `v0.2.0`）推送到 GitHub。
3. 在 Folinov Console 的「设置 → 关于与更新 → 发布新版本」里填写版本号、主下载地址与镜像地址。
