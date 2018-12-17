---
title: "新blog编写博文wiki"
date: 2018-12-15T02:34:19-05:00
description: "纸鸢"
weight: 20
draft: false 
---

### 博客wiki

* 提交说明
  
博客内容及文章目前托管于：https://github.com/atsblog/blog

提交博文只需要把文章md文件提交到：blog/content/post/目录下。
如 blog/content/post/106.md

博客服务器每分钟会自动从github地址同步一次新改动。

* 编写习惯说明

目前文章的标题、作者、时间、标签tag是使用一个固定的开头格式进行标注如，本人的md开头部分：

```
---
title: "新blog编写博文wiki"
date: 2018-12-15T02:34:19-05:00
description: "纸鸢"
tags: [ "ats", "wiki"]
weight: 20
draft: false 
---

正文开始......
```


* github说明

目前博客内容托管在github上，如果想投稿可以pull request进行投稿，如果想长期编写博客，可以联系直接添加到项目成员中。

* 客户端工具推荐-vscode

如果没有好用的客户端工具，推荐`vscode`

安装插件：`Markdown All in One`、`Markdown Preview Enhanced`

预览使用`Preview`，编写使用`All in One`很方便，例如选择图片它会自动帮你查找目录下的图片文件，选择即可。

`vscode`也有终端控制台，带预览地编写完成md文件可以直接在终端控制台进行git操作把文章提交到git仓库。