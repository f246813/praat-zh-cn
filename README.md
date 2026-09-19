# Praat 6.4.61 简体中文界面补丁

非官方 Windows x64 汉化版，基于 Praat 6.4.61。

汉化只替换界面显示文字；内部英文命令、对象类型、公式和脚本语法保持不变。
鼠标停留在已汉化的菜单、按钮、标签或选项上约 0.9 秒，可查看对应英文原文。

## 下载

- [Windows x64 完整包](https://github.com/f246813/praat-zh-cn/releases/download/v3.5/praat-6.4.61-zh-v3.5-windows-x64.zip)：解压后运行 `Praat_zh.exe`，不会覆盖官方原版
- [源码补丁包](https://github.com/f246813/praat-zh-cn/releases/download/v3.5/praat-6.4.61-zh-v3.5-source-patch.zip)：不含可执行文件或完整官方源码
- [v3.5 发布说明与 SHA-256](https://github.com/f246813/praat-zh-cn/releases/tag/v3.5)

程序未获签名。请核对完整包内的 `Praat_zh.exe.sha256` 和发布页面列出的压缩包 SHA-256

## 主要变化

- 英文悬停提示统一为 0.9 秒
- 汉化进一步覆盖至各个小窗口和警告
- 修复并复核此前发现的翻译问题

## 源码与构建

对应的[官方 Praat 6.4.61 源码](https://github.com/praat/praat.github.io/releases/tag/v6.4.61)由 Praat 项目发布。汉化源码补丁位于上方的补丁包；将其应用到对应版本后，可参照包内的 `patch/build/Build-PraatZh.ps1` 构建。GitHub 自动生成的本仓库“Source code”压缩包不是 Praat 源码或汉化补丁。

本版正式词库共 6,865 条，已完成首轮逐条审校；构建和回归测试通过。手册正文、用户数据、文件名、公式和脚本按设计保留原文

Praat 整体按 [GPL-3.0-or-later](https://praat.org/manual/License.html) 发布；本汉化修改亦按同一许可提供。Praat 的版权和商标归原权利人所有，本项目与官方团队无关联。
