# Chapter 1 The Yocto Project 开发任务手册 <!-- omit in toc -->

- [1.1 欢迎](#11-欢迎)
- [1.2 其他](#12-其他)

## 1.1 欢迎
欢迎阅读Yocto Project开发任务手册！这篇文档提供在Yocto Project环境（例如开发在目标设备上运行的嵌入式Linux系统以及用户空间应用）中进行开发所需的相关步骤。在本文档中，相关的操作步骤被分类到了同一章节，根据内容的不同，有些章节会给读者提供详细的操作步骤，有些章节则只提供概括性的介绍。

本文档将提供如下信息：

- 帮助你熟悉Yocto Project。例如：如何搭建一套构建主机并使用Yocto Project代码仓库
- 如何提交改动到Yocto Project。这些改动可以是改进，新功能，或是bug修复。
- 使用Yocto Projcet开发镜像及应用时的日常操作，例如：如何创建layer，自定义image，编写recipe...

本文档不提供如下信息：

- 重复性的逐步指导：例如[Yocto Project应用开发和eSDK手册](http://www.yoctoproject.org/docs/2.7/sdk-manual/sdk-manual.html)已包含如何安装用来开发目标设备应用的SDK的详细步骤。
- 参考或概念资料：这些有对应的文档介绍，例如系统变量的说明及解释会包含在[Yocto Project参考手册](http://www.yoctoproject.org/docs/2.7/ref-manual/ref-manual.html)中。
- 不由Yocto Project定义的，公开的信息/细节： 例如如何使用Git可以在网上找到更官方更好的指导。

## 1.2 其他
本文档包含很多方面的内容，如果你想完全理解这些内容，推荐阅读更多补充资料。如果想了解Yocto Project的介绍性信息，可以访问[Yocto Project](https://www.yoctoproject.org/)网站。如果你希望能在不了解Yocto Project的情况下能快速构建镜像，请参考[Yocto Project快速构建](http://www.yoctoproject.org/docs/2.7/brief-yoctoprojectqs/brief-yoctoprojectqs.html)文档。

在[Yocto Project参考手册](http://www.yoctoproject.org/docs/2.7/ref-manual/ref-manual.html)里，你可以找到链接和其他文档的综合列表。