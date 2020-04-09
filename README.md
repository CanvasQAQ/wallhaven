# wallhaven

You can use it to get the wallpaper from wallhaven.cc

本项目github地址：[CanvasQAQ/wallhaven](https://github.com/CanvasQAQ/wallhaven)

本项目gitee地址：[CanvasQAQ/wallhaven](https://gitee.com/CanvasQAQ/wallhaven)

发布地址主要在github上，gitee仅定期同步。

## 项目来源及计划

本项目根据原作者cooperun的[wallhaven项目](https://github.com/Cooperun/webspider/tree/master/wallpaperheaven)更改而来，初始计划仅仅是以能用为目的(作者一年没更新了QAQ)

之后有余力会改的更好用一点。

今后设计构想：

- 构建GUI
- 新增语言选择，方便国内外友人使用
- 提供查重功能，不再下载文件夹中已有的图片

## 使用指南

本项目测试环境为python3.8，理论上python3都能够支持，同时需要安装两个第三方库。可以使用如下指令安装：

`pip install -r requirement.txt`

如果感觉安装较慢或报错，可以升级pip：

`python -m pip install --upgrade pip`

以及使用清华源，在指令后加上：

`-i https://pypi.tuna.tsinghua.edu.cn/simple`

`python wallhaven_download.py`直接运行，依据提示输入各项参数。

建议：

- 选择最新的时候不要将点赞数设定过高，以免图片文件都被过滤掉
- 文件夹可以直接使用`./pic`即直接放在该py文件所在文件夹的pic子文件夹中。
