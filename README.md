# 我的自定义键盘

通过 [AHK](https://www.autohotkey.com)实现的自定义键盘，当前支持移动光标，快速输入符号

## 使用

下载 `autohotkey` ，双击加载[脚本]("/src/main.ahk")，或者编译为 exe 文件使用

## 说明

当前支持 3 种输入模式，分别为

- `9模式` 快速移动光标，删除文本
- `3模式` 快速输入数字，删除文本
- `分号模式` 快速输入符号，同时有伴生的 `引号模式`,用来补全`分号模式`中括号输入的不足

具体规则通过代码查看： [9 模式](/src/modules/mode-9.ahk)，[3 模式](/src/modules/mode-3.ahk)，[分号模式](/src/modules/mode-semi.ahk)，[引号模式](/src/modules/mode-quote.ahk)
