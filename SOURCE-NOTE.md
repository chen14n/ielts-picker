# 源码状态说明（SOURCE-NOTE）

## 当前发布内容

本仓库当前提供的是配套资料；Windows 成品安装包在 [Releases](../../releases) 页面提供，不纳入仓库目录：

- Releases 附件：`ielts-picker-setup.exe`（页面展示名「雅思取词安装包」），双击安装后使用；
- `wordbook-template/`：4 个空白词库 Excel 模板（仅表头）；
- `README.md`、`docs/使用说明.txt`：功能与使用文档。

## 为什么仓库里没有源代码

打包本工具的原始 Python 工程文件（`main.py`、`requirements.txt`、`build.ps1`、资源图标等）在整理发布前一度丢失，目前**未能随本次仓库一并提供**。为避免误导，本仓库不放置反编译产物，也不声称提供可构建的源码。

## 后续计划

- 若原始源码找回，将补充到仓库根目录，并附上 `requirements.txt`、构建脚本与截图；
- 历史技术栈：Windows + Python 3.9+，PyInstaller `--onefile --windowed` 打包；
- 在此之前，欢迎通过 Issue / Discussion 反馈功能问题与使用建议。

## 关于二次开发

MIT 协议允许你使用、修改和分发本项目；但在缺少源码的情况下，直接对成品 exe 做二次修改并不现实。如果你希望基于它改造自己的划词工具，建议参考 README 中描述的功能与配置，自行实现；需要思路上的交流也欢迎提 Issue。
