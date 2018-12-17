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

* 如果使用工具-hugo

如果只简单使用markdown编辑工具可以只参考上面两个小节手动编辑头部+正文内容即可。

如果希望使用工具建议使用hugo，可以安装hugo客户端
用法：
```
hugo new post/106.md
```

其实也只是帮忙生成头部信息。

* github说明

目前博客内容托管在github上，如果想投稿可以pull request进行投稿，如果想长期编写博客，可以联系直接添加到项目成员中。