---
layout: post
title: 初来乍到
subtitle: 记录一些心得
tags: [网站]
---

哈哈，想来也是，大家都是初来乍到，只不过是“愿意多做”和“懒得多做”的区别。

在此记录一下建立github托管网站的心得。
对于我将来主要使用的post功能，有以下几点：
1. 提交md文件到_post文件夹，文件命名须使用英文，形式为#2023-03-13-标题#这种形式。
2. 在md文件头部，需要
---
layout: post
title: Flake it till you make it
subtitle: Excerpt from Soulshaping by Jeff Brown
cover-img: /assets/img/path.jpg
tags: [books, test]
---
3. post使用的图片分为：封面图片cover-img，缩略图thumbnail-img（默认与封面图相同），分享到社交网站上显示的图片share-img。
4. 添加图片的格式如下：thumbnail-img: /assets/img/thumb.png
5. 如果想要添加额外的栏目，可以在_config.yml中navbar-links添加，基本是一些链接或者pdf。
