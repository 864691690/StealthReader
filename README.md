# StealthReader

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows-blue" alt="Platform">
  <img src="https://img.shields.io/badge/Python-3.10%2B-green" alt="Python">
  <img src="https://img.shields.io/badge/License-MIT-yellow" alt="License">
</p>

> 🐟 摸鱼阅读器 - 上班摸鱼，神不知鬼不觉

## 简介

StealthReader 是一款专为**办公场景**设计的桌面阅读工具。它把小说文字直接「印」在你的屏幕上——没有窗口边框、没有标题栏，同事走过完全看不出来你在看书。

## 特性

### 🛡️ 四大隐蔽模式

| 模式 | 说明 |
|------|------|
| **变色龙模式** 🦎 | 自动检测窗口下方的屏幕颜色作为背景，文字颜色自动反转，完美融入任何背景 |
| **幽灵模式** 👻 | 鼠标在窗口上时正常显示，移开后自动变透明 |
| **系统级防截屏** 🛡️ | 截图、录屏、屏幕共享时窗口完全不可见 |
| **老板键** ⌨️ | 一键隐藏/呼出窗口，托盘图标同步消失 |

### 📚 阅读功能

- **本地 TXT 阅读**：智能分页、章节导航、进度记忆
- **Legado 同步**：连接手机端「阅读」APP Web 服务
- **编码兼容**：自动识别 UTF-8 / GBK

### 🖱️ 操作方式

- 移动窗口：按住拖动
- 翻页：滚轮 / 方向键 / 空格
- 所有功能：右键菜单

## 快速开始

### 方式一：直接使用

下载 `dist/StealthReader.exe`，双击运行（需要管理员权限）。

### 方式二：从源码运行

```bash
# 克隆仓库
git clone https://github.com/864691690/StealthReader.git
cd StealthReader

# 安装依赖
pip install -r requirements.txt

# 运行
python main.py

# 或编译为 EXE
pyinstaller -F -w -i read.ico -n StealthReader main.py
```

## 快捷键

| 按键 | 功能 |
|------|------|
| `Esc`（可自定义） | 老板键：显示/隐藏 |
| `↓` / `→` / `空格` | 下一页 |
| `↑` / `←` | 上一页 |
| 鼠标滚轮 | 翻页 |
| 右键 | 功能菜单 |

## 系统要求

- Windows 10 2004+（防截屏功能需要）
- 管理员权限（全局键盘钩子需要）

## 截图

（待补充）

## 开发

```bash
# 安装开发依赖
pip install PyQt5 requests keyboard pyinstaller

# 运行调试
python main.py

# 编译发布版本
pyinstaller -F -w -i read.ico -n StealthReader main.py
```

## 许可证

[MIT License](LICENSE)

## 免责声明

本工具仅供学习交流 PyQt5 开发技术，请合理安排工作时间。

---

<p align="center">
  Made with ❤️ by <a href="https://github.com/864691690">864691690</a>
</p>
