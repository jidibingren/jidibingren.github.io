---
layout: post
title: MarkdownEditing的使用
tags: 
- Markdown
categories: Study
<!-- description:  -->
---
##快捷键 

> - command+control+[1-6] 标题
> - command+option+v      `[linkname](link)`
> - command+option+r 	  `[linkname][reference link]
						  [reference link]:link` 
> - command+shift+k       `![imagename](image path)`

##连接

> - [OmniMarkupPreviewer](https://github.com/timonwong/OmniMarkupPreviewer)
> - [MarkdownEditing](https://github.com/SublimeText-Markdown/MarkdownEditing#key-bindings)
> - [Markdown语法](http://www.appinn.com/markdown/basic.html)

##配置指南

Jacman 主题提供了丰富的配置属性，可以实现您对主题的自定义。配置文件`_config.yml`位于主题根目录下。本次更新对配置文件进行了较大调整，如您之前就使用了 Jacman，也需要您根据以下指南进行相应的修改。

###属性功能
- **菜单 menu**
默认没有启用 `/tags` 和 `/categories`页面，如果需要启用请在博客目录下的`source`文件夹中分别建立`tags` 和 `categories`文件夹每个文件夹中分别包含一个`index.md`文件。内容为：

```
layout: tags (或categories)
title: tags (或categories)
---
```

