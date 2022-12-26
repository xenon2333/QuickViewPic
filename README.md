# QuickViewPic
A small tool to view images quickly.

一个简单的快速看图小工具。

程序灵感来自[@hamoyy](https://meta.appinn.net/t/topic/38641)，全部使用[aardio](https://www.aardio.com)编写。

作者邮箱：xenon2333@qq.com
## 使用场景
- 需要重复快速查看指定图片，如查询尺码表。
- 需要将多张截图“钉”在屏幕上，且要求快速来回切换。
- 快速浏览本地保存的表情包，并一键复制到剪贴板，用于聊天工具中。
## 基本介绍
启动后程序会自动吸附在屏幕边缘，鼠标移动到窗口上则会唤出。

上下移动鼠标可选择项目，同时会在一旁自动显示图片。

最上方的按钮点击即可弹出菜单，可进行设置或退出操作。

右键点击列表项可一键复制当前选中项到剪贴板。

设置将在程序退出时自动保存至%LocalAppData%目录下的QuickViewPic\config.cfg（剪贴板数据除外）。

## 模式
### 默认
自动从程序启动目录读取图片。

**支持的图片格式**：**jpg**、**png**、**bmp**。（下同）

### 自定义目录
由用户指定图片根目录，程序会自动扫描含有图片的子目录并供用户选择。程序会从用户选择的目录读取图片。
### 自定义图片列表
由用户自行指定图片的路径及显示顺序。
### 剪贴板
从剪贴板中导入位图并显示。

支持剪贴板监视及自动保存功能。

获取位图的方式包括但不限于：
- QQ截图工具
- 浏览器页面复制

可反复导入多张位图。

## 注意事项
- 尽量不要浏览太大的图片，可能会导致程序卡顿甚至崩溃。
- 图片像素大小超过屏幕大小时会自动缩小图片，会导致图片失真。
- 程序一旦退出，已缓存的剪贴板数据将会丢失！
## 截图
- 界面：

![screenshot](./Screenshots/Screenshot_1.png)

![screenshot](./Screenshots/Screenshot_2.png)

- 设置界面：

![screenshot](./Screenshots/Screenshot_3.png)

![screenshot](./Screenshots/Screenshot_4.png)

![screenshot](./Screenshots/Screenshot_5.png)

![screenshot](./Screenshots/Screenshot_6.png)

- 隐藏时的小提示

![screenshot](./Screenshots/Screenshot_7.png)

## 详细介绍
[动图演示](https://flowus.cn/share/ce8c4370-5d95-4c10-8bad-b24465376c31)

[帮助文档](https://flowus.cn/share/8326c462-726c-4fe1-a829-fcf710e1f191)

## 其它要说的
虽然我跟[@hamoyy](https://meta.appinn.net/t/topic/38641)要了他的源码，不过他之前是用易语言写的，而我上一次用易语言还是几年之前的事情了，因此我没能打开看源码。这个程序是根据我的观察，基于原有的功能先仿制了一个，再根据我个人需要添加了一些功能。

同时这个程序是我第一个发到github上的作品（其实本人也之前写过几个，不过都是给自己用的），希望大家多多支持，帮我测试一下。另外本人并非计算机相关专业的学生，敲代码纯属个人喜好，程序难免会有不足之处，恳请各位指正。
