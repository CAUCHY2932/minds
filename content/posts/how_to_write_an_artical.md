---
title: "如何写一篇博客"
subtitle: ""
date: 2020-12-31T22:16:39+08:00
lastmod: 2020-12-31T22:16:39+08:00
draft: false
author: "CAUCHY2932"
authorLink: ""
description: ""

tags: []
categories: []

hiddenFromHomePage: false
hiddenFromSearch: false

featuredImage: ""
featuredImagePreview: ""

toc:
  enable: true
math:
  enable: false
lightgallery: false
license: ""
---

<!--more-->

## 新建文章

使用 `hugo new posts/index.md` 命令新建一篇文章

下述内容中的第 11 行，包含了图片之类的数据，建议，减少图片，尽量以文字形式呈现。

可能是以 yaml 格式进行存储的。

```
weight: 4
title: "Basic Markdown Syntax"
date: 2019-12-01T21:57:40+08:00
lastmod: 2020-01-01T16:45:40+08:00
draft: false
author: "Sunt Programator!"
authorLink: "https://suntprogramator.dev/"
description: "This article shows the basic Markdown syntax and format."
resources:
- name: "featured-image"
  src: "featured-image.png"

tags: ["Markdown", "HTML"]
categories: ["Markdown"]

lightgallery: true
```

##  后记

### 排版

参考 [中文排版指北](https://github.com/sparanoid/chinese-copywriting-guidelines) 进行排版

### 图片代替

```
:computer: 可以表示电脑，但是遗憾的是，这种语法可以被github、typora渲染，但不能所有的网站接受，比如本网站
```

## 命令

```
hugo new xx.md # 新建文档，注意，如果没有填充内容，可能会报错
hugo # 编译生成静态文件
hugo serve -D # 本地服务器部署服务
```

