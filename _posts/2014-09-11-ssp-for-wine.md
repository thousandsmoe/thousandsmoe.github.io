---
layout: post
title: wine 下 ssp 透明问题的解决
date: 2014-09-11 09:38:14
---

之前的 wine 运行 ssp.exe 时，并未解决透明问题。

也就是说，即使在勾选“窗口透明”选项的时候，亦无法打开窗口透明。

经过某种程度上的 hack ，将 ssp 中判断逻辑修改，强制打开透明后表现完美。

下载：[百度网盘](http://pan.baidu.com/s/1pJpyYGN)