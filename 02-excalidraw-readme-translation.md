# Excalidraw README 本地化示例（节选）

原文来源：https://github.com/excalidraw/excalidraw（README.md）

原文长度：约 180 词　｜　译者：刘佳琦

## 原文

### Features

The Excalidraw editor (npm package) supports:

- 💯 Free & open-source.
- 🎨 Infinite, canvas-based whiteboard.
- ✍️ Hand-drawn like style.
- 🌓 Dark mode.
- 🏗️ Customizable.
- 📷 Image support.
- 😀 Shape libraries support.
- 🌐 Localization (i18n) support.
- 🖼️ Export to PNG, SVG & clipboard.
- 💾 Open format - export drawings as an `.excalidraw` json file.
- ⚒️ Wide range of tools - rectangle, circle, diamond, arrow, line, free-draw, eraser...
- ➡️ Arrow-binding & labeled arrows.
- 🔙 Undo / Redo.
- 🔍 Zoom and panning support.

### Excalidraw.com

The app hosted at [excalidraw.com](https://excalidraw.com/) is a minimal showcase of what you can build with Excalidraw. Its [source code](https://github.com/excalidraw/excalidraw/tree/master/excalidraw-app) is part of this repository as well, and the app features:

- 📡 PWA support (works offline).
- 🤼 Real-time collaboration.
- 🔒 End-to-end encryption.
- 💾 Local-first support (autosaves to the browser).
- 🔗 Shareable links (export to a readonly link you can share with others).

We'll be adding these features as drop-in plugins for the npm package in the future.

### Quick start

**Note:** following instructions are for installing the Excalidraw [npm package](https://www.npmjs.com/package/@excalidraw/excalidraw) when integrating Excalidraw into your own app. To run the repository locally for development, please refer to our [Development Guide](https://docs.excalidraw.com/docs/introduction/development).

Use npm or yarn to install the package.

```
npm install react react-dom @excalidraw/excalidraw
# or
yarn add react react-dom @excalidraw/excalidraw
```

Check out our [documentation](https://docs.excalidraw.com/docs/@excalidraw/excalidraw/installation) for more details!

### Contributing

- Missing something or found a bug? [Report here](https://github.com/excalidraw/excalidraw/issues).
- Want to contribute? Check out our [contribution guide](https://docs.excalidraw.com/docs/introduction/contributing) or let us know on [Discord](https://discord.gg/UexuTaE).
- Want to help with translations? See the [translation guide](https://docs.excalidraw.com/docs/introduction/contributing#translating).

## 译文

### 功能特性

Excalidraw 编辑器（npm 包）支持以下功能：

- 💯 免费、开源。
- 🎨 无限画布式白板。
- ✍️ 手绘风格。
- 🌓 深色模式。
- 🏗️ 可自定义。
- 📷 图片支持。
- 😀 形状库支持。
- 🌐 本地化（i18n）支持。
- 🖼️ 导出为 PNG、SVG，或复制到剪贴板。
- 💾 开放格式：可将绘图导出为 .excalidraw 的 JSON 文件。
- ⚒️ 多种工具：矩形、圆形、菱形、箭头、直线、自由绘制、橡皮擦……
- ➡️ 箭头绑定与带标签箭头。
- 🔙 撤销/重做。
- 🔍 可缩放和平移。

### Excalidraw.com

托管在 excalidraw.com 的应用程序是一个极简示例，展示用 Excalidraw 能做出什么。其源代码也包含在此仓库中，该应用程序的功能包括：

- 📡 PWA 支持（可离线使用）。
- 🤼 实时协作。
- 🔒 端到端加密。
- 💾 本地优先（自动保存到浏览器）。
- 🔗 可分享链接（可导出为只读链接分享给他人）。

未来我们会将这些功能以即插即用插件的形式加入 npm 包。

### 快速开始

注意：以下说明适用于在将 Excalidraw 集成到自己的应用中时安装 Excalidraw npm 包的情形；如需在本地运行本仓库进行开发，请参考我们的开发指南。

使用 npm 或 yarn 安装该包。

```
npm install react react-dom @excalidraw/excalidraw
# or
yarn add react react-dom @excalidraw/excalidraw
```

有关更多详细信息，请查看我们的文档！

### 参与贡献

- 若发现缺少功能或遇到 bug，请在此处报告。
- 若想要贡献，请查看我们的贡献指南或在 Discord 上告知我们。
- 若想要协助翻译，请参阅翻译指南。

## 术语对照

| 英文 | 中文 | 说明 |
|---|---|---|
| npm package | npm 包 | |
| canvas-based | 画布式 | |
| Local-first | 本地优先 | 不用“本地存储”，因为原文强调的是数据优先保存在本地这一设计取舍，并非强调存储动作 |
| End-to-end encryption | 端到端加密 | |
| drop-in plugins | 即插即用插件 | 意译，指无需改造即可加入 npm 包的插件 |
| repository | 仓库 | 与“包（package）”区分：仓库是整个代码存放处，包是发布出去的模块 |

## 译注

**译注 1：代码块里的 # or 保留原文不译。**

代码块属于可直接复制执行的内容，保持原文可确保开发者复制后无需修改即可运行；若把注释译成中文，会让同一代码块中出现中英混排，反而增加判断成本。

**译注 2：Local-first 不用“本地存储”。**

Local-first 是一个专业术语，指数据优先存在本地、可离线使用；“本地存储”更像是技术手段，读者会理解成“数据存在硬盘上”，与原文括号里的“自动保存到浏览器”的意思不贴合。

**译注 3：链接文字已译出，超链接未保留。**

原文中的 source code、documentation 等是带链接的词组；译文只保留了文字，原文区的链接仍可点击查证。如需完整本地化，应保留原有链接指向。

**译注 4：保留 emoji。**

emoji 属于视觉符号，不算文字；翻译只处理文字部分，符号保持原样既不失真，也保留了每条的视觉标识。
