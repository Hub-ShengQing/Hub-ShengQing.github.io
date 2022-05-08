SQ.Blog —— 自由定制的轻量级博客
======
SQ.Blog 是基于 Jekyll 的个人静态博客网站。

* * *

目录
-----------------
  - [特点](#特点)
  - [演示](#演示)
  - [配置](#配置)
  - [文章](#文章)
  - [Disqus 评论](#disqus-评论)
  - [百度统计](#百度统计)
  - [引用](#引用)
  - [鼓励](#鼓励)

* * *

### 特点

* 完全响应的简洁清爽的主题

* 优化了移动设备显示效果

* 自由定制的静态式网页

* 添加有文章分享功能

* 支持用户评论留言


* * *

### 演示

首页预览：

![Main page preview](https://github.com/artemsheludko/zolan/blob/master/images/zolan-main-page.png?raw=true)

文章页预览：

![Post page preview](https://github.com/artemsheludko/zolan/blob/master/images/zolan-post.png?raw=true)

* * *

### 配置

为了在本地运行此博客，你得在博客的文件夹目录下运行 `bundle install` 命令去安装依赖项，然后运行 `jekyll serve` 或 `bundle exec jekyll serve` 命令开启 Jekyll 服务器。

* * *

### 文章

发表文章时，在 `\_posts` 文件目录下创建一个 markdown 格式的文件。每篇文章头部需添加[头信息（YAML front matter block）](https://jekyllrb.com/docs/posts/#creating-post-files)，其通常用于设置布局或其他元数据。这是一个简单的示例：

      ---
      layout: 指定布局文件
      title: 题目
      date: 2018-08-23 16:04:00 +0300
      image: 封面
      tags: 标签
      ---

在 **/assets/images/** 目录下添加文章图片。

关于标签，不要在单词之间输空格，如：
 `Ruby on Rails`，而是像这样：`ruby-on-rails` 或 `Ruby_on_Rails`。

* * *

### Disqus 评论

SQ.Blog 支持 [Disqus](https://disqus.com/) 评论系统。

打开 `_data/settings.yml`，将 `disqus-identifier` 的属性值改为你的 [Disqus 账户简称](https://help.disqus.com/customer/portal/articles/466208)。

      Comment Section (Disqus)
      disqus-identifier: brown # 给 Disqus 评论系统设置简称. 如 brown

这便是博客配置 Disqus 的全部步骤了。倘若评论无法加载，首先确保你已[向 Disqus 注册你的网站](https://help.disqus.com/customer/portal/articles/466182-publisher-quick-start-guide)（第一步）。或可查看 [Disqus 故障排除指南](https://help.disqus.com/customer/portal/articles/472007-i-m-receiving-the-message-%22we-were-unable-to-load-disqus-%22)。

* * *

### 百度统计

若要添加百度统计，打开 `_data/settings.yml`，输出申请的 `key`。

* * *

### 引用

我使用了下表列出的脚本、字体或其他文件：

*   [Iconfont](https://www.iconfont.cn/)
*   [FitVids.js](http://fitvidsjs.com/)
*   [Medium’s Image Zoom](https://github.com/fat/zoom.js)
*   [jQuery.com](https://jquery.com/)

* * *

### 鼓励
<p>若你喜欢我的博客网站，
<p align="center"><b>请点个 ☆ Star，感谢你的支持 ❤️！</b></p>
