# maupassant-hugo
Maupassant theme, ported to Hugo.
这个模板基于 https://github.com/JokerQyou/maupassant-hugo

用模板做的个人blog https://timx.cn/
#### 1.添加了右侧卡片式的个人介绍
![card](https://user-images.githubusercontent.com/8891076/42434621-73549158-8386-11e8-8224-9f4fec7d62b1.jpg)
#### 2.添加了右侧日历显示
![card](https://user-images.githubusercontent.com/8891076/42434626-7797fb24-8386-11e8-9e03-51705ed818d7.jpg)
#### 3.添加了gittalk评论（之前加了gitment，后来发现gittalk更优秀就替换成gittalk）
![card](https://user-images.githubusercontent.com/8891076/42434624-75d5b1b4-8386-11e8-89ab-99ea0f8ff111.jpg)
#### 4.原模板中手机端显示右侧栏会被隐藏，修改后在手机端让右侧栏显示在文章的下方。
![card](https://user-images.githubusercontent.com/8891076/42434972-a90ba010-8387-11e8-8c0f-6d0db19f5f58.jpg)
#### 5.添加了背景动画


### 注意事项

1.要增加菜单在md文件中加入type: standalone

2.文章要有评论在md文件中加入gitment: true

3.文章要有目录在md文件中加入TableOfContents: true

```
---
title: "博客开通"
date: 2018-07-04T17:44:01+08:00
categories: [其他]
tags: [其他]
gitment: true
TableOfContents: true
---
```