# Chapter 1 The Yocto Project 开发任务手册 <!-- omit in toc -->

- [1.1 欢迎](#11-%e6%ac%a2%e8%bf%8e)
- [1.2 其他](#12-%e5%85%b6%e4%bb%96)

## 1.1 欢迎
欢迎阅读Yocto Project开发任务手册！这篇文档提供在Yocto Project环境（例如开发在目标设备上运行的嵌入式Linux系统以及用户空间应用）中进行开发所需的相关步骤。本文档将相关过程分组为higher-level章节进行说明。根据不同的话题，章节可能包含概括性的介绍或者细节步骤。

本文档将提供如下信息：

- 帮助你熟悉Yocto Project。例如：如何搭建一套构建主机并使用Yocto Project代码仓库
- 如何提交改动到Yocto Project。这些改动可能是改进，新功能，或是bug修复。
- 使用Yocto Projcet开发image及应用时“日常”所需进行的任务。例如，如何创建layer，自定义image，编写recipe...

本文档不提供如下信息：

- 重复性的逐步指导：例如《Yocto Project 应用开发以及可扩展软件开发工具包（eSDK）手册》包含如何安装用来开发目标硬件应用的SDK的详细说明。
- 参考或概念资料：这些有对应的文档介绍，例如系统变量由《Yocto Project参考文档》介绍。
- 不由Yocto Project定义的，公开的信息/细节： 例如如何使用Git可以在网上找到更官方更好的指导。

## 1.2 其他
本文档包含很多方面的内容，希望完全理解这些内容，推荐阅读更多补充资料。如果想了解Yocto Project的介绍性信息，可以访问Yocto Project网站。如果你希望能在不了解Yocto Project的情况下能快速构建image，请参考《Yocto Project 快速构建手册》。

在《Yocto Project 参考文档》里，你可以找到链接和其他文档的综合列表。