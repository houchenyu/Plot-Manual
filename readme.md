# Plot Manual

## Motivation

在科技论文写作时，经常需要画各种各样的实验图。同时为了排版美观，还需要对实验图做各种细微的调整。

而利用代码进行画图时，由于参数多而繁琐，无法全部都记在脑中，经常需要上网搜索对应功能的代码，而网上的教程五花八门，良莠不齐，所以在画图时费时费力。



所以，我最近花了几天的时间，简单整理了一下之前论文写作时常画的图，已经调整图的方法。

## Language

* R
* Python (Coming soon)

## Grpah

* Scatter 散点图
* Line 折线图
* stackbar 条形图

## Required

* R
  * * IDE: Rstudio
  * * package：ggplot2
  * * knowledge: R grammar
* Python
  * * balabalabala

## Instruction

目前只有R语言版本，因为之前主要使用的是R。 后续将继续完善Python画图的方法，因为Python在某些方面确实功能比R完善。



R语言中有两个画图体系， 一个是基于plot的基础画图，另一个是基于ggplot2的高级画图，我对于每一种图形都实现了这两个版本，任君选择。



本库中的文件主要分为两种类型：1、可编辑的R Markdown文件，可以直接对文件进行修改。 2、对应的html文件，可以直观地查看代码最终效果。 ​	

| 功能       | 对应代码    |
| ---------- | ----------- |
| 散点图     | ScatterPlot |
| 折线图     | LinePlot    |
| 条形图     | BarPlot     |
| 调整坐标轴 | Axis        |
| 调整图例   | Legend      |



PS：有些功能的实现方法不仅仅只有我提供的一种，如果有更好的建议请联系： houcy@zjut.edu.com



