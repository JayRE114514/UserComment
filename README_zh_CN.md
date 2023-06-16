# UserComment Plugin

UserComment Plugin 是一个用于IDA的插件，用于显示用户添加的注释。

## 注意

这个插件是基于Hook的方式实现的，这意味着它只能获取并保存安装该插件之后用户添加的注释。

<b>对于在安装插件之前添加的用户注释，该插件无法获取到。</b>

## 安装

将 `UserComment.py` 文件复制到IDA插件目录的 `plugins` 文件夹下。

## 使用方法

打开注释窗口的三种方式:
1. 菜单中选择 View/Open subviews/Comments
2. 使用快捷键（Ctrl-Shift-C）
3. 按下 Ctrl-!，然后选择 "Comments"

## 功能

- 提供注释窗口, 显示用户添加的注释，包括汇编代码和伪代码中的注释。
- 支持多种类型的注释（common comments, repeatable comments, anterior comments, and posterior comments）。

## 贡献

如果你发现任何问题、有改进建议或想要添加新功能，请提交 issue 或 pull request。

希望这对你有所帮助！如果有其他问题，请随时提问。
