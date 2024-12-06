# openai-to-ppt
## 基本原理
1. openai生成markdown
2. markdown转ppt（选型如下）
```
以下是几个可以将Markdown转换为PowerPoint演示文稿的TypeScript库：

### 1. Marp

Marp是一个强大的Markdown演示工具，具有以下特点：
- 基于CommonMark规范，使用简单的Markdown语法创建幻灯片
- 支持扩展语法，如图片、数学公式等
- 内置主题，支持自定义CSS主题
- 可将Markdown直接转换为HTML、PDF和PPT格式
- 提供VS Code扩展和命令行工具

### 2. @marp-team/marp-cli

这是Marp的命令行工具，具有以下功能：
- 将Marp/Marpit的Markdown文件转换为HTML、PDF、PPT和图片
- 使用`--pptx`选项可将Markdown文件转换为PPT格式
- 生成的PPTX文件包含已渲染的Marp幻灯片和Marpit演讲者注释

### 3. pptxgenjs

pptxgenjs是一个JavaScript库，用于创建PowerPoint演示文稿，具有以下特点：
- 兼容Microsoft PowerPoint、Apple Keynote等演示软件
- 提供简洁的API来添加幻灯片、文本、图形、图片等元素
- 支持Angular、React、ES6和TypeScript

### 4. 其他选项

- **md2pptx**：将Markdown转换为PPT演示文稿的工具（支持MultiMarkdown子集）
- **Markdown_PPT_Converter**：使用Python将Markdown文件转换为PPT
- **inkppt**：基于Ink开发的命令行工具，可在终端渲染Markdown文件，类似PPT

这些库提供了多种选择，开发者可以根据需要选择合适的工具来将Markdown转换为PPT格式。
```
