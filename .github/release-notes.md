## 下载

| 文件 | 适用环境 |
|---|---|
| **FEFW-Save-Editor-…-windows.zip** | Windows。解压后运行 `FEFW Save Editor.exe`，无需安装 Python。 |
| FEFW-Save-Editor-…-source.zip | Linux、macOS 或其他装有 Python 3.10 及以上版本的环境。先运行 `pip install -r requirements.txt`，再运行 `python editor.py`。 |

**操作前请关闭游戏，并备份整个存档目录。** 首次写入某个存档槽时，编辑器也会在该槽旁边保留一份原始存档 `<slot>.bak`。

`.exe` 未签名。Windows SmartScreen 若提示「Windows 已保护你的电脑」，可选择「更多信息 → 仍要运行」（*More info → Run anyway*）。有些杀毒软件也可能误报 PyInstaller 打包的程序。也可以用 Python 运行源码压缩包里的同一程序。

设置保存在 `.exe` 所在目录，请把程序放在有写入权限的位置，避开 `Program Files`。
