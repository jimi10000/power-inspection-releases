# 电巡工作台

适用于变电站与配电线路巡检、照片记录、缺陷整改、设备台账和报告交付的 Windows 桌面应用。

## 下载

[下载最新版本](https://github.com/jimi10000/power-inspection-releases/releases/latest)

支持 Windows 10 / 11（64 位）。下载 Release 中的 `PowerInspectionDesk-版本号-Setup.exe`，运行并按提示安装。首次打开后，把机器码发给软件提供者，收到对应授权码或 `.pxlicense` 文件后激活。

## 应用内更新

从 1.1.0 起，点击左侧“软件更新”，可检查、下载并安装 GitHub 正式版本，也可导入 `.pxupdate` 本地更新包。可选择启动时检查；安装前由使用者确认。

旧 1.0 版本请先运行新版安装包升级一次，以后可在应用内更新。

更新会保留当前 Windows 用户的巡检数据、照片及授权。使用数据与授权页面中的完整 JSON 备份功能，可另行备份或迁移工作数据。

## 发布文件

- `PowerInspectionDesk-版本号-Setup.exe`：首次安装和覆盖升级。
- `PowerInspectionDesk-版本号.pxupdate`：在软件中导入的本地更新包。
- `update.json`：供应用内更新读取的签名清单。

本仓库仅用于应用分发，不公开应用源码。授权管理工具和签发私钥不存放于本仓库。
