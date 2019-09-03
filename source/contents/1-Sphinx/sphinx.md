# Sphinx 简介

Sphinx，本意是“狮身人面像”，作为本教材主要介绍的工具，Sphinx 是一个基于 Python 开发的文档生成工具，由Georg Brandi开发，其第一个公开版本在2008年3月21日发布。目前的 <a href="https://docs.python.org/zh-cn/3/" target="_blank">Python 官方文档</a>就是基于 Sphinx 开发生成的。

用 Sphinx 开发文档，有以下几个亮点：
- 多种输出格式：HTML，LaTeX，ePub，手册，纯文本
- 层次结构清晰：通过简单的文本树定义，能链接到同层和上下层的文本
- 自动生成目录：生成索引以及其他模块的目录
- 代码高亮：通过 Pygments 组件实现代码高亮

我们可以 Sphinx 想象成一种文档框架，通过构建 Sphinx 项目搭建起文档的框架，进行内容创作就是往框架中填充内容，Sphinx 会将单调的重复工作抽象化，通过自动函数解决一些常见的问题，如突出显示标题索引和特殊代码等。

Sphinx 使用 reStructuredText 等标记语法来提供文档控制，标记语言的介绍与语法将在后面的章节详细介绍。