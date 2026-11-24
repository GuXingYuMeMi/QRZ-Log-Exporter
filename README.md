# QRZ 日志导出器 v1.0.0

本项目是一个非官方的 QRZ 个人 Logbook 本地导出工具，只读取用户本人已登录、可见的通联日志。

下载最新版
点击右侧的 [Releases](你的Releases页面链接) 页面，下载最新的 `QRZLogExporter.zip` 或 `QRZLogExporter-source.zip`。

功能特性
- **本地桌面界面**：Windows 使用独立窗口，Linux 使用本地浏览器界面。
- **安全登录**：手动完成 QRZ 登录，**不保存账号密码**。
- **简单导出**：列表页字段，按 QRZ 当前上限每页 200 条处理。
- **详细导出**：可补充 RST、经纬度、距离、方位、QSL / LoTW / eQSL 等详情页字段。
- **多格式支持**：支持 CSV、JSON、ADIF 导出。
- **自定义配置**：支持通过文件夹图标选择 ADI 保存位置；可配置请求间隔，默认 10 秒。
- **多平台支持**：提供 Windows EXE 与 Linux 启动脚本。

快速使用指南 (How to use)

Windows 用户 (10/11)
1. 下载并解压 `QRZLogExporter.zip`。
2. 双击运行 `.exe` 文件，打开独立窗口。
3. 在弹出的界面中手动登录 QRZ 账号。
4. 选择导出格式（CSV/JSON/ADIF）和保存路径，点击导出。

Linux 用户 / 开发者
1. 下载并解压 `QRZLogExporter-source.zip`。
2. 确保系统已安装所需环境（如 Python/Node 等，根据你的实际情况补充）。
3. 运行启动脚本。
4. 在弹出的本地浏览器页面中完成登录和导出。

⚠️ 注意
- 本项目与 QRZ.com 无关联，也未获得 QRZ.com 认可或背书。
- 请仅导出你自己的日志，并自行确认使用方式符合 QRZ.com 服务条款。
- 由于默认请求间隔为 10 秒，导出大量日志可能需要一些时间，请耐心等待。

许可证 (License)
本项目采用 [MIT 许可证](LICENSE)。
