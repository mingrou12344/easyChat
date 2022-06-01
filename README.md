# easyChat

PC端微信助手（非web微信版）：定时发送信息；群发信息；自动回复等

最新编辑日期：2022/06/01

有疑问请邮件交流：[sujinltenjoy@gmail.com](mailto:sujinltenjoy@gmail.com)

## 前言

之前使用过的itchat等工具都是基于web版网页微信的。自从网页微信无法登陆之后，之前的工具都失效了。因此，本人采用uiaumation对微信进行~~暴力~~操作，就有了本仓库。并且用~~自学了三年的图形界面水平~~写了个简易ui供大家使用。

## 支持功能

- 群发消息
- 定时发送消息
- 自动回复（随缘开发ing）

> 注意事项：请在使用过程中严格遵守输入格式，否则程序会自动退出。（要去考虑一个个边界条件太麻烦了，我直接采取一个鸵鸟政策）

## 文件说明

**ui_auto_wechat.py**是对PC版微信进行的各种操作实现代码。内部代码简易，支持自由DIY。

**wechat_gui.py**是编写的图形界面，在图形界面中调用对微信的操作。由于本人太懒，直接放弃美工，后期边做边改吧。

**wechat_gui.exe**是打包好的exe程序，可以直接下载进行使用。

## 图形界面

<img src="C:\Users\15716\lib\常用信息\GUI.png" alt="GUI" style="zoom: 80%;" />

​										**图形界面示意图**

### 使用步骤

1. 点击“选择微信打开路径”，在目录下选择微信的可执行exe文件。

2. 点击“添加用户”，输入要发送信息的用户名（在搜索框第一个展示的名字，如下所示）。

   ![搜索示例](pictures/搜索示例.png)

3. 在文本框中输入要发送的内容。也可以点击发送文件，在目录中选择要发送的文件。随后点击发送即可。
4. （可选）如果要进行定时发送，点击下方的“添加时间”按钮，按照规定的格式添加时间。随后点击“开始定时”，当时间达到列表中的指定时间时，便会将指定的消息发送给所有的指定用户。

