# 耻辱墙

访问地址: https://wallofshame.github.io

在这个信息流充斥的时代, 大众普遍对于发生的事情只有几天甚至几小时的记忆, 而我们历史的长河中有很多事情, 不论是好事还是坏事, 都是不该被忘记的.

"耻辱墙" 的愿景是能希望够帮助大众记住历史长河中的一小部分事情: 那些企业和大 V 所做过的 "耻辱" 的事情, 一是帮他们记住自己曾做过的事情, 毕竟 "人行天地间, 做了事就要承担后果", 你不想承担不想负责是不行的; 二是供后人后人查阅, 以免踩雷.

## FAQ

### 之前曾有过这样的站点吗?

我看到之前有人也做过尝试，但是似乎都没有很好的维持下去. 本站目前克服了几乎所有会导致前人无法维持下去的因素, 唯有一点暂时没有克服, 那就是本站目前仍需要人工介入来维持网站健康运行, 这是很关键的一点, 据我观察很多前人失败的例子都是由于个人精力不济或者个人意志转移导致的. 这一点我还没有完美的解决方法, 愿大家申请成为本站管理员权限一起参与维护.

其他已经克服了的会导致无法持续的因素以后再细聊.

### 本站内容界限

本站的内容仅限于社会上的企业和大 V 的 "耻辱" 行径. 不要试图发布政治话题.

## 文章贡献说明

### 目录结构

文章请直接创建在 [本仓库](https://github.com/wallofshame/wallofshame.github.io) 的 `content/posts/` 目录下, 如果有图片, 在 `content/posts/` 目录下创建与文章同名的目录 (称为资源目录), 并将图片放入此目录中, 并在文章中使用相对路径指向图片.

示例:

```
content/
  posts/
    demo-article.md
    demo-article/
      demo-image.png
```

要想在 demo-article.md 里引用图片 demo-image.png, 只需要使用如下的 markdown 语法:

```
![](demo-image.png)
```

注意图片路径不必是 `demo-article/demo-image.png`, 仅需是 `demo-image.png`.

### 文章头部信息 (front matter)

```
---
title: 一女生实名指控曾受沈阳性骚扰
date: 2018-04-09
tags: 沈阳
description: 这位女生名叫许红云，她希望更多被沈阳侵扰的女生勇敢地站出来，勇敢地面对过去和现在，才能看到未来。
---
```

### 来源说明格式

```
---
原文来自公号名称/网站名称：~~[文章标题](原文链接)~~
   
作者：XXX
---
```
