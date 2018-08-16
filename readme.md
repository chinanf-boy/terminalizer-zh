# terminalizer [![explain]][source] [![translate-svg]][translate-list]

[explain]: http://llever.com/explain.svg
[source]: https://github.com/chinanf-boy/Source-Explain
[translate-svg]: http://llever.com/translate.svg
[translate-list]: https://github.com/chinanf-boy/chinese-translate-list

「 🦄 录制 你的 terminal 和 生成 gif 文件 , {找了好久} 」

[more]: https://github.com/chinanf-boy/chinese-translate-list

---

## 校对 ✅

<!-- doc-templite START generated -->
<!-- time = '2018 7.31' -->

翻译的原文 | 与日期 | 最新更新 | 更多
---|---|---|---
[commit] | ⏰ 2018 7.31 | ![last] | [中文翻译][more]
<!-- doc-templite END generated -->

[last]: https://img.shields.io/github/last-commit/faressoft/terminalizer.svg
[commit]: https://github.com/faressoft/terminalizer/tree/a0b6574e78440c544d2bfea41865004b610bd8ab


### 贡献

欢迎 👏 勘误/校对/更新贡献 😊 [具体贡献请看](https://github.com/chinanf-boy/chinese-translate-list#贡献)

## 生活

[help me live , live need money 💰](https://github.com/chinanf-boy/live-need-money)

---

# Terminalizer

[![npm](https://img.shields.io/npm/v/terminalizer.svg)](https://www.npmjs.com/package/terminalizer)
[![npm](https://img.shields.io/npm/l/terminalizer.svg)](https://github.com/faressoft/terminalizer/blob/master/LICENSE)
[![Gitter](https://badges.gitter.im/join_chat.svg)](https://gitter.im/terminalizer/Lobby)
[![Unicorn](https://img.shields.io/badge/nyancat-approved-ff69b4.svg)](https://www.youtube.com/watch?v=QH2-TGUlwu4)
[![Tweet](https://img.shields.io/badge/twitter-share-76abec.svg)](https://goo.gl/QJzJu1)

> 录制您的终端并生成动画 gif 图像

<p align="center"><img src="/img/demo.gif?raw=true"/></p>

录制命令行 jusT cOol 👌 🦄!

> 如果你这么认为,请给我一个支持`star`和 a`follow`😘

一边建,一边听[喵喵喵](https://www.youtube.com/watch?v=QH2-TGUlwu4)😛

---

<p align="center"><img src="/img/trending.png?raw=true"/></p>

---

# 目录

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [特征](#%E7%89%B9%E5%BE%81)
- [下一步是什么](#%E4%B8%8B%E4%B8%80%E6%AD%A5%E6%98%AF%E4%BB%80%E4%B9%88)
- [安装](#%E5%AE%89%E8%A3%85)
- [入门](#%E5%85%A5%E9%97%A8)
  - [压缩](#%E5%8E%8B%E7%BC%A9)
- [用法](#%E7%94%A8%E6%B3%95)
  - [配置](#%E9%85%8D%E7%BD%AE)
  - [录制](#%E5%BD%95%E5%88%B6)
  - [播放](#%E6%92%AD%E6%94%BE)
  - [渲染 gif](#%E6%B8%B2%E6%9F%93gif)
  - [分享](#%E5%88%86%E4%BA%AB)
  - [生成](#%E7%94%9F%E6%88%90)
- [配置](#%E9%85%8D%E7%BD%AE-1)
  - [Recording](#recording)
  - [Delays](#delays)
  - [GIF](#gif)
  - [Terminal](#terminal)
  - [Theme](#theme)
  - [水印](#%E6%B0%B4%E5%8D%B0)
  - [Frame 框](#frame-%E6%A1%86)
    - [空框](#%E7%A9%BA%E6%A1%86)
    - [Window 框](#window%E6%A1%86)
    - [浮动框架](#%E6%B5%AE%E5%8A%A8%E6%A1%86%E6%9E%B6)
    - [坚固的框架](#%E5%9D%9A%E5%9B%BA%E7%9A%84%E6%A1%86%E6%9E%B6)
    - [没有标题的实心框架](#%E6%B2%A1%E6%9C%89%E6%A0%87%E9%A2%98%E7%9A%84%E5%AE%9E%E5%BF%83%E6%A1%86%E6%9E%B6)
    - [style 提示](#style%E6%8F%90%E7%A4%BA)
- [常问问题](#%E5%B8%B8%E9%97%AE%E9%97%AE%E9%A2%98)
  - [如何支持 ZSH](#%E5%A6%82%E4%BD%95%E6%94%AF%E6%8C%81zsh)
- [问题](#%E9%97%AE%E9%A2%98)
- [执照](#%E6%89%A7%E7%85%A7)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# 特征

- 高度可定制.
- 跨平台 (Linux,Windows,MacOS) .
- `window frames` 规则.
- `font` 规则.
- `colors` 规则.
- `styles`与`CSS` 规则.
- 水印.
- 在渲染之前编辑帧并调整延迟.
- 通过步长值跳过帧以减少渲染帧的数量.
- 在图像上渲染图像而不是捕获屏幕以获得更好的质量.
- 配置能力:
  - 能捕获的命令终端 (bash,powershell.exe,yourOwnCommand 等)
  - 当前的工作目录.
  - 列和行数的显式值.
  - GIF 质量和重复.
  - 帧延迟.
  - 帧之间的最大空闲时间.
  - 光标样式.
  - 字体.
  - 字体大小.
  - 线高.
  - 字母间距.
  - 主题.

# 下一步是什么

- 网站来啰[terminalizer.com](https://terminalizer.com).
- 主目录中的全局配置.
- 该`share`命令上传录制文件并获取在线播放器的链接.
- 该`Generate`命令为录制文件生成 Web 播放器.

# 安装

你需要先安装[Node.js](https://nodejs.org/en/download/),使用此命令全局安装该工具:

```bash
npm install -g terminalizer
```

<p align="center"><img src="/img/install.gif?raw=true"/></p>

> 仍然面临一个问题?检查[问题](#issues)部分或打开一个新问题.

如果安装失败,您可能需要安装开发工具来构建`C++`插件.

⚠️Tinnerizer 使用了一些`C++`需要建筑的插件. 在我们发布第一个包含针对不同操作系统的预构建二进制文件的稳定版本之前,您可能需要安装一些工具来构建. 尝试以下操作,如果它们无法解决您的安装问题,请检查<https://github.com/nodejs/node-gyp#installation>.

对于 MacOS

```bash
xcode-select --install
```

对于 RHEL,CentOS,Scientific Linux,Fedora

```bash
yum update
yum groupinstall "Development Tools"
```

对于 Debian,Ubuntu 和衍生品

```bash
sudo apt-get update
sudo apt-get install build-essential
```

对于 openSUSE/SUSE

```bash
zypper refresh
zypper update
zypper install -t pattern devel_C_C++
```

适用于 Arch Linux 及其衍生产品

```bash
sudo pacman -Syyu
sudo pacman -S base-devel
```

验证安装

```bash
gcc -v
make -v
```

# 入门

使用开始录制终端`record`命令.

```bash
terminalizer record demo
```

一个名为的文件`demo.yml`将在当前目录中创建. 您可以使用任何编辑器打开它来编辑配置和录制的帧. 您可以使用以下内容重播录制内容`play`命令.

```bash
terminalizer play demo
```

现在让我们将我们的录音呈现为 GIF 动画.

```bash
terminalizer render demo
```

## 压缩

GIF 压缩尚未实施. 现在我们推荐<https://gifcompressor.com>.

# 用法

> 你可以使用`--help`选项以获取有关命令及其选项的更多详细信息

```bash
terminalizer <command> [options]
```

## 配置

> 在当前目录中生成配置文件

```bash
terminalizer config
```

## 录制

> 录制终端并创建录制文件

```bash
terminalizer record <recordingFile>
```

选项

    -c, --config   Overwrite the default configurations [string]
    -d, --command  The command to be executed           [string] [default: null]

例子

    terminalizer record foo                      Start recording and create a recording file called foo.yml
    terminalizer record foo --config config.yml  Start recording with your own configurations

## 播放

> 在终端上播放录音文件

```bash
terminalizer play <recordingFile>
```

选项

    -r, --real-timing   Use the actual delays between frames as recorded        [boolean] [default: false]
    -s, --speed-factor  Speed factor, multiply the frames delays by this factor [number] [default: 1]

## 渲染 gif

> 将录制文件渲染为动画 gif 图像

```bash
terminalizer render <recordingFile>
```

选项

    -o, --output   A name for the output file                                      [string]
    -q, --quality  The quality of the rendered image (1 - 100)                     [number]
    -s, --step     To reduce the number of rendered frames (step > 1) [number] [default: 1]

## 分享

> 上传录制文件并获取在线播放器的链接

```bash
terminalizer share <recordingFile>
```

## 生成

> 为录制文件生成 Web 播放器

```bash
terminalizer generate <recordingFile>
```

# 配置

默认值`config.yml`文件存储在项目的根目录中. 执行以下命令将其复制到当前目录.

> 使用任何编辑器编辑复制的`config.yml`,然后使用`-c`选项以覆盖默认值.

```bash
terminalizer config
```

## Recording

- `command`: 指定要执行的命令`/bin/bash -l`,`ls`或任何其他命令. 默认是`bash`对于`Linux`要么`powershell.exe`对于`Windows`.
- `cwd`: 指定当前工作目录路径. 默认值是当前工作目录路径.
- `env`: 导出其他 ENV 变量,在开始录制时由脚本读取.
- `cols`: 显式设置列数或使用`auto`获取 shell 的当前列数.
- `rows`: 显式设置行数或使用`auto`获取 shell 的当前行数.

## Delays

- `frameDelay`: 以 ms 为单位的帧之间的延迟. 如果值是`auto`使用实际录制延迟.
- `maxIdleTime`: 帧之间的最大延迟 (ms) . 如果被忽略了`frameDelay`未设置为`auto`. 设置`auto`防止限制最大空闲时间.

## GIF

- `quality`: 生成的 GIF 图像的质量 (1 - 100) .
- `repeat`: 重复 GIF 的次数:
  - 如果价值是`-1`,玩一次.
  - 如果价值是`0`,无限循环.
  - 如果 value 是正数,则循环`n`倍.

## Terminal

- `cursorStyle`: 光标样式可以是其中之一`block`,`underline`, 要么`bar`.
- `fontFamily`: 您可以使用计算机上安装的任何字体`Monaco`要么`Lucida Console` (类似 CSS 的列表) .
- `fontSize`: 字体的大小 (以像素为单位) .
- `lineHeight`: 以像素为单位的线条高度.
- `letterSpacing`: 字母之间的间距,以像素为单位.

## Theme

您可以使用以下 CSS 格式之一设置终端的颜色:

- 十六进制: `#FFFFFF`.
- RGB: `rgb(255, 255, 255)`.
- HSL: `hsl(0, 0%, 100%)`.
- 名称: `white`,`red`,`blue`.

> 您可以使用该值`transparent`太.

分配给终端颜色的默认颜色为:

- background: ![#ffffff](https://placehold.it/15/ffffff/000000?text=+) `transparent`
- foreground: ![#afafaf](https://placehold.it/15/afafaf/000000?text=+) `#afafaf`
- cursor: ![#c7c7c7](https://placehold.it/15/c7c7c7/000000?text=+) `#c7c7c7`
- black: ![#232628](https://placehold.it/15/232628/000000?text=+) `#232628`
- red: ![#fc4384](https://placehold.it/15/fc4384/000000?text=+) `#fc4384`
- green: ![#b3e33b](https://placehold.it/15/b3e33b/000000?text=+) `#b3e33b`
- yellow: ![#ffa727](https://placehold.it/15/ffa727/000000?text=+) `#ffa727`
- blue: ![#75dff2](https://placehold.it/15/75dff2/000000?text=+) `#75dff2`
- magenta: ![#ae89fe](https://placehold.it/15/ae89fe/000000?text=+) `#ae89fe`
- cyan: ![#708387](https://placehold.it/15/708387/000000?text=+) `#708387`
- white: ![#d5d5d0](https://placehold.it/15/d5d5d0/000000?text=+) `#d5d5d0`
- brightBlack: ![#626566](https://placehold.it/15/626566/000000?text=+) `#626566`
- brightRed: ![#ff7fac](https://placehold.it/15/ff7fac/000000?text=+) `#ff7fac`
- brightGreen: ![#c8ed71](https://placehold.it/15/c8ed71/000000?text=+) `#c8ed71`
- brightYellow: ![#ebdf86](https://placehold.it/15/ebdf86/000000?text=+) `#ebdf86`
- brightBlue: ![#75dff2](https://placehold.it/15/75dff2/000000?text=+) `#75dff2`
- brightMagenta: ![#ae89fe](https://placehold.it/15/ae89fe/000000?text=+) `#ae89fe`
- brightCyan: ![#b1c6ca](https://placehold.it/15/b1c6ca/000000?text=+) `#b1c6ca`
- brightWhite: ![#f9f9f4](https://placehold.it/15/f9f9f4/000000?text=+) `#f9f9f4`

## 水印

您可以在生成的 GIF 图像中添加水印徽标.

<p align="center"><img src="/img/watermark.gif?raw=true"/></p>

    watermark:
      imagePath: AbsolutePathOrURL
      style:
        position: absolute
        right: 15px
        bottom: 15px
        width: 100px
        opacity: 0.9

- `watermark.imagePath`: 计算机上图像的绝对路径或 URL.
- `watermark.style`: 将 CSS 样式 (camelCase) 应用于水印图像,如调整大小.

## Frame 框

终结器附带预定义的框架,您可以使用它们使您的 GIF 图像看起来很酷.

- `frameBox.type`: 可`null`,`window`,`floating`, 要么`solid`.
- `frameBox.title`: 显示框架或标题`null`.
- `frameBox.style`: 应用自定义 CSS 样式或覆盖当前样式.

### 空框

没有框架,只有你的录制.

<p align="center"><img src="/img/frames/null.gif?raw=true"/></p>

> 别忘了添加一个`backgroundColor`下`style`.

    frameBox:
      type: null
      title: null
      style:
        backgroundColor: black

### Window 框

<p align="center"><img src="/img/frames/window.gif?raw=true"/></p>

    frameBox:
      type: window
      title: Terminalizer
      style: []

### 浮动框架

<p align="center"><img src="/img/frames/floating.gif?raw=true"/></p>

    frameBox:
      type: floating
      title: Terminalizer
      style: []

### 坚固的框架

<p align="center"><img src="/img/frames/solid.gif?raw=true"/></p>

    frameBox:
      type: solid
      title: Terminalizer
      style: []

### 没有标题的实心框架

<p align="center"><img src="/img/frames/solid_without_title.gif?raw=true"/></p>

    frameBox:
      type: solid
      title: null
      style: []

### style 提示

您可以禁用默认阴影和边距.

<p align="center"><img src="/img/frames/solid_without_title_without_shadows.gif?raw=true"/></p>

    frameBox:
      type: solid
      title: null
      style:
        boxShadow: none
        margin: 0px

# 常问问题

### 如何支持 ZSH

为 Linux 录制的默认命令是`bash -l`. 您需要将默认命令更改为`zsh`.

- 在当前目录中生成配置文件

```bash
terminalizer config
```

- 在首选编辑器中打开生成的配置文件.
- 改变`command`至`zsh`:


    command: zsh

- 您可能需要更改字体,检查终端中使用的字体:


    fontFamily: "Meslo for Powerline, Meslo LG M for Powerline"

- 使用`-c`覆盖配置文件的选项:

```bash
terminalizer record demo -c config.yml
```

# 问题

> 加载共享库时出错: libXss.so.1: cannot open shared object file: No such file or directory

解:

```bash
sudo yum install libXScrnSaver
```

> 加载共享库时出错: libgconf-2.so.4: cannot open shared object file: No such file or directory

解:

```bash
sudo apt-get install libgconf-2-4
```

# 执照

该项目受 MIT 许可.
