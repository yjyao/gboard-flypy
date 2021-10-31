# 在 GBoard 上使用小鹤音形

谷歌的 GBoard 输入法已经支持小鹤双拼方案。
但并不支持小鹤音形。
本词库利用 GBoard 的「personal dictionary」功能
允许用户在 GBoard 上使用音形方案。

注意：
音形只能作为辅助码。
帮助你快速打出单字。
小鹤音形官方的四码上屏功能
并不能通过此方案实现。
而使用 GBoard 最大的好处
也正在于其没有四码上屏的限制。
得以提供智能造句的益处。

## 涵盖范围

本词库基于小鹤音形官方词库。
去除了冗余和不适用部分。
并有一些个人偏好和词条。

- 冗余部分：
  - 去除了纯双音词条。
    GBoard 已内置小鹤双拼方案。
    保留了简码词条。
  - 去除了日语假名。
    GBoard 支持多语言。
    有日语需求的用户
    可自行添加日语键盘。
- 不适用部分：
  - 命令词条等
- 其他：
  - 去除了小字字根
    及自成一字的部首字根。
  - 英文词左右增加了空格。

## 使用（安装）

### 导入至 GBoard

1. 准备词库
  1. 下载 gboard-dictionary.txt
  1. 打包压缩成 .zip 文件（例：gboard-dictionary.zip）
  1. 上传至设备
1. 打开 GBoard Chinese (Simplified) personal dictionary
  1. 打开 GBoard
  1. 点击齿轮图标进入设置
  1. 依次点击
     Dictionary >
     Personal Dictionary >
     Chinese (Simplified)
1. 导入词库
  1. 点击右上角的「点点点」展开菜单
  1. 点击「Import」
  1. 选择压缩好的词库包（例：gboard-dictionary.zip）
  1. 导入可能需要若干分钟。
     甚至导致黑屏。
     请耐心等待。
     不要中断。

### 替换词库

有时我们需要替换现有词库。
比如大批量删去词条。
GBoard  11.1.04 不支持清空词库。
但可以通过重置 GBoard 数据实现。

注意：
重置数据意味着同时重置其他词库
以及*用户设置*。
请务必事先做好备份。

要重置 GBoard 数据
（以原生安卓 12 系统为例）：

1. 打开系统设置
1. 找到 GBoard 
1. 点击「Storage & cache」
1. 点击「Clear storage」
