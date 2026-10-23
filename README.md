<p align="center"><img src="assets/icon.png" width="100" alt="拾回 图标"></p>

# 拾回

**看清废纸篓中的文件，找到可验证的来源，再决定恢复或清理。**

![产品介绍](assets/banner.svg)

[![下载](https://img.shields.io/badge/下载-DMG-brightgreen)](https://github.com/jhtnba/shihui/releases/latest) [![版本](https://img.shields.io/badge/版本-0.1.0-blue)](https://github.com/jhtnba/shihui/releases) [![系统](https://img.shields.io/badge/平台-macOS-black)](docs/INSTALL.md)

[下载应用](https://github.com/jhtnba/shihui/releases/latest) · [使用方法](docs/GUIDE.md) · [更新记录](CHANGELOG.md) · [常见问题](docs/FAQ.md) · [反馈问题](https://github.com/jhtnba/shihui/issues/new/choose)

## 为谁准备

看清废纸篓中的文件，找到可验证的来源，再决定恢复或清理。 如果你希望在 Mac 上完成废纸篓检查与恢复，可以从当前版本开始尝试。

## 主要功能

| 功能 | 具体用途 |
|---|---|
| 废纸篓集中查看 | 查看当前用户及已挂载磁盘中可访问的用户废纸篓。 |
| 来源路径识别 | 结合应用记录、Finder 还原记录和严格核对的系统历史识别来源，无法确认则显示未知。 |
| 恢复与定位 | 恢复到原位置或指定目录；目标重名时跳过，不覆盖，成功后在 Finder 显示。 |
| 多种浏览视图 | 图标、列表、分栏和画廊，结合系统缩略图与预览。 |
| 搜索与排序 | 按名称和来源路径搜索，按大小、移入时间、标签等字段排序。 |
| 后台变化监测 | 窗口关闭后可继续监测废纸篓变化，菜单栏入口可重新打开。 |

## 下载与安装

当前版本 **0.1.0（build 7）**。当前发布包面向 **Apple Silicon Mac**，要求 **macOS 13 或更新版本**。

1. 前往 [Releases](https://github.com/jhtnba/shihui/releases/latest)，下载 `拾回-0.1.0-macOS.dmg`。
2. 打开 DMG，把 App 拖到“应用程序”。
3. 从“应用程序”启动。详细步骤见[安装指南](docs/INSTALL.md)。

## 第一次使用

1. 首次打开后，如无法读取废纸篓，前往“系统设置 → 隐私与安全性 → 完全磁盘访问权限”添加拾回，再退出并重新打开。
2. 连接需要查看的外置磁盘，等待后台读取；使用搜索查找名称或记录的来源路径。
3. 选择文件后查看来源、大小、时间和标签，使用列表表头调整排序。

[查看完整操作指南 →](docs/GUIDE.md)

## 使用前须知

- 不是磁盘数据恢复软件，不能找回已彻底删除或被覆盖的数据。
- 无法确认来源时显示未知，不根据同名文件猜测原路径。
- 权限、文件系统、历史保留情况及外置磁盘连接状态会影响来源识别。
- 文件夹大小不递归统计，不代表能够释放的真实磁盘空间。
- 永久删除和清倒不可恢复。本版确认框回车默认执行，Esc 取消，请认真核对。
- 未提供安全擦除、强制清空、自动清空或删除保护。

## 问题反馈

通过 [Issues](https://github.com/jhtnba/shihui/issues/new/choose) 描述复现步骤、macOS 版本、应用版本和预期结果。截图请遮挡个人路径、用户名和文件内容；不要提交密码、令牌或原始私人文件。

## 更多应用

[咪咪](https://github.com/jhtnba/mimi) · [IINB](https://github.com/jhtnba/iinb) · [拾回](https://github.com/jhtnba/shihui) · [应用总览](https://github.com/jhtnba/mac-apps)

本页面只列出已有资料能核实的功能，不把计划功能写成已实现；未做过的兼容性和交互测试不作保证。
