**[介绍](pages/about.md)**

极简的博客风格，点击头像切换到夜间模式。

**配置**

1. 如果使用自己的域名，`CNAME`文件里的内容请换成你自己的域名，然后 CNAME 解析到`用户名.github.com`

2. 如果使用 GitHub 的的域名，请删除`CNAME`文件,然后把你的项目修改为`用户名.github.io`

3. 修改`pages/about.md`中关于我的内容

4. 修改`_config.yml`文件，具体作用请参考注释

5. 清空`post _posts`目录下所有文件，注意是清空，不是删除这两个目录

6. 网站的 logo 和 favicon 放在了`static/img/`下，替换即可，大小无所谓，图片比例最好是 1:1

**使用**

文章放在`_posts`目录下，命名为`yyyy-MM-dd-xxxx-xxxx.md`，内容格式如下

```yaml
---
layout: mypost
title: 标题
categories: [分类1, 分类2]
---
文章内容，Markdown格式
```

文章资源放在`posts`目录，如文章文件名是`2019-05-01-theme-usage.md`，则该篇文章的资源需要放在`posts/2019/05/01`下。
