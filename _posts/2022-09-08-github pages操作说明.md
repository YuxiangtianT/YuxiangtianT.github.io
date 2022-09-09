---
layout: post
title: github pages操作说明
categories: Blog
description: github pages操作说明
keywords: github pages, github desktop
topmost: true
---
# github pages操作说明

## 前言

本文主要介绍用github pages创建个人主页，用到的工具有github desktop和VS code(或者typora)。创建过程中可能会需要挂vpn，可以考虑[sockboom](https://sockboom.cool/auth/register?affid=158913)链接。**文中的图片有部分可能看不清，可以缩放网页或者单独查看图片**。[github pages操作说明ppt](https://github.com/YuxiangtianT/YuxiangtianT.github.io/tree/main/PPT/github%20pages%E6%93%8D%E4%BD%9C%E8%AF%B4%E6%98%8Eppt)

## github pages创建流程

1.创建gtihub账号后，点击Create repository新建仓库。

![图片1.png](https://s2.loli.net/2022/09/08/LygibZWuIM1sRGp.png)

2.在创建仓库界面，Repository name输入格式为： **<你的用户名username>.github.io** 。再勾选Add a README file为仓库添加ReadMe文件。点击Create repository创建仓库。

![图片2.png](https://s2.loli.net/2022/09/08/UQeBxdhiGfwTYIy.png)

3.在创建完个人仓库后，进入仓库。在Settings->Pages可以看到github pages相关信息。等待几分钟后刷新，页面上会显示可以通过<你的用户名username>.github.io访问你创建的个人主页。

![图片3.png](https://s2.loli.net/2022/09/08/drzpU5vKbO4m62u.png)

![图片4.png](https://s2.loli.net/2022/09/08/BHfTeuLdVD6Egc9.png)

4.到这一步，个人网页已经创建好了，并可以通过网址访问，但此时还需要配置个人网页的主题。下面将介绍克隆仓库/上传文件，并以配置主题为示例。

![图片5.png](https://s2.loli.net/2022/09/08/u6Db1wxsh2HVAiK.png)

## 克隆仓库/上传文件（推荐Github Desktop工具）

Github Desktop是github的客户端平台，在上面克隆仓库/上传文件比较方便，就可以不用Git输入命令行那种比较繁琐的方式。可以参考[主题链接](https://github.com/YuxiangtianT/YuxiangtianT.github.io)，也可以自己在网上查找[jekyll主题](https://jekyllthemes.io/free)。

### 克隆仓库

我们在github上经常需要获取别人的源代码，一般有两种方式去获取：直接下载或者fork别人的仓库到自己的仓库。

#### 直接下载

直接在别人的github仓库主页，点击Code->Code->Download ZIP，就可以下载别人源代码的zip压缩包。

![图片6.png](https://s2.loli.net/2022/09/08/M8O2xDtV4eQycRF.png)

#### fork别人的仓库到自己的仓库

点击右上角的fork按钮，会跳转到fork页面，然后直接点击Create fork按钮，就可以看到别人仓库里的内容已经fork到自己的仓库了。

![图片7.png](https://s2.loli.net/2022/09/08/LBaq5DTECgHIn86.png)

![图片8.png](https://s2.loli.net/2022/09/08/Ih3xHTtMXiP428z.png)

### 在Github Desktop的克隆仓库操作

1.选择想要克隆的仓库，然后直接点击clone XXX仓库，再点击clone。

![图片9.png](https://s2.loli.net/2022/09/08/D7KX6NhVEFstJI2.png)

![图片10.png](https://s2.loli.net/2022/09/08/KJYnQq3pw29Pg8N.png)

2.然后选择你准备怎么使用这个仓库。如果你想对这个仓库作出贡献，你可以选择To contribute to the parent project；如果是为了个人目的，就选择For my own purposes。这里我们是为了把这个主题配置到我们的个人网页上，所以选择第二个。按照相同方式，可以把其他仓库也克隆到客户端上，在github desktop上可以看到这些已经克隆的仓库，然后可以在克隆仓库的本地文件中查看各个仓库中包含的文件。

![图片11.png](https://s2.loli.net/2022/09/08/eEhmFBiHRgCPXrV.png)

![图片12.png](https://s2.loli.net/2022/09/08/KD87BykdczGYle2.png)

### 上传文件

我们在选择好主题之后，就需要把主题的源代码上传到我们自己的个人仓库中，才能生成对应的主题页面。上传的方式也有很多种，这里主要介绍两种：直接Add file或者通过Github Desktop上传。

#### Add file

1.在github网页上，点击Code->Add file，可以选择创建新文件或者更新文件。

![图片13.png](https://s2.loli.net/2022/09/08/Yv6xGeqNtlQaRZW.png)

2.在新增/修改文件页面，选择需要上传的文件，然后添加对应的描述内容，就可以将文件上传到github页面。但这种方式比较适合上传的**文件数量比较少**的情况。

![图片14.png](https://s2.loli.net/2022/09/08/5YnsRQmTytbKD2i.png)

![图片15.png](https://s2.loli.net/2022/09/08/Pfig5rJuapKdNLv.png)

#### 通过Github Desktop上传

1.打开刚刚克隆下来的仓库的本地文件，我们的目的是将mzlogin.github.io文件中的主题配置复制到YuxiangtianT.github.io文件中。**注意：不要将.git文件复制过去了。**

![图片16.png](https://s2.loli.net/2022/09/08/1cXhqTzfkMSRQZK.png)

![图片17.png](https://s2.loli.net/2022/09/08/1Itr7P6UYVne5yW.png)

2.在Github Desktop的YuxiangtianT.github.io仓库中，可以在左侧看到有哪些文件需要上传，然后在左下角添加这次修改文件的信息描述，点击Commit to main提交commit，然后点击Push origin就可以把文件push到github上。

![图片18.png](https://s2.loli.net/2022/09/08/Cc9Y43pLMNqOxFv.png)

![图片19.png](https://s2.loli.net/2022/09/08/KY3EsUH6gMLxWqN.png)

3.刷新github页面，可以看到文件已上传，然后刷新个人主页，就可以看到主题已经配置到个人主页上了，最后就是对主题的配置进行修改，使其变为自己的博客。

![图片20.png](https://s2.loli.net/2022/09/08/6gEuTpUMXvDhJK4.png)

![图片21.png](https://s2.loli.net/2022/09/08/tPDLJqnMOrmauNX.png)

## 主题介绍

在配置主题之前，先从主题的各个页面，对主题进行一个简要的介绍。这个主题主要有五个页面：首页、分类、维基、链接和关于。

### 首页

![图片36.png](https://s2.loli.net/2022/09/09/cXu7RiUBPN6rvdE.png)

这个主题的首页页面主要包括这几个内容：

1.个人信息。在页面的顶部和底部都有个人的相关信息。

2.文章。这是首页页面的主要部分，可以查看博客中的所有文章。

3.搜索和标签。搜索可以直接输入你想要搜索的关键字查找文章，在搜索下面会显示你所有文章的标签，点击对应的标签，会跳转到分类页面中所有包含此标签的文章。

4.热门仓库。这里会显示你的github中的比较热门的仓库，供别人参考。

### 分类

![图片37.png](https://s2.loli.net/2022/09/09/TDk1RwIo6hZgBHW.png)

这个主题的分类页面主要包括这几个内容：

1.标签以及含有该标签的文章列表。

2.搜索和标签列表。点击对应的标签可以跳转到含有该标签的文章列表。

### 维基

![图片38.png](https://s2.loli.net/2022/09/09/l7osiNSDQjgmuk9.png)

这个主题的维基页面主要包括这几个内容：

1.标签以及含有该标签的文章列表。这里有包含一级标签和二级标签。比如Android是一级标签，而Android-Tools是二级标签。

2.搜索和标签列表。点击对应的标签可以跳转到含有该标签的文章列表。

### 链接

![图片39.png](https://s2.loli.net/2022/09/09/K81XqPofF7Bg3LG.png)

这个主题的链接页面主要包括这几个内容：

1.与你相关的链接。

2.友情链接。

3.评论。

### 关于

![图片40.png](https://s2.loli.net/2022/09/09/tTD8IwS7NlpG3ko.png)

这个主题的关于页面主要包括这几个内容：

1.个人信息。

2.联系方式。

3.你学会的技术。

## 主题配置

以这个主题为例，这里讲解如何去配置主题里的内容。如果选择其他主题，对应的ReadMe文件中也是有相关的配置说明，请尽量按照配置说明来配置主题。**修改配置文件时，各个网页（即.html文件）基本是不需要修改的。**

### 修改主题基本配置

网站的配置基本都集中在_config.yml文件中，将其中与个人信息相关的部分替换成你自己的，比如网站的url、title、subtitle等。**注意修改其中的网址，一定要修改为你的个人主页网址或者域名。**

![图片22.png](https://s2.loli.net/2022/09/08/DJCd9MQabqpONsE.png)

![图片23.png](https://s2.loli.net/2022/09/08/TREChZqAuWvHpjo.png)

### 评论模块

目前支持disqus、gitment、gitalk、utterances和beaudar评论工具，选用其中一种来构建你的评论模块，这里使用的是[gitalk](https://github.com/gitalk/gitalk#install)。它们各自的官方配置指南链接在_config.yml文件的Comments一节里都贴出来了。

![图片24.png](https://s2.loli.net/2022/09/08/1c8PyoAsDFiY4j7.png)

gitalk的安装使用参考[gitalk中文说明](https://github.com/gitalk/gitalk/blob/master/readme-cn.md)，安装部分在主题里已经配置好了，这里直接看使用部分。

![图片25.png](https://s2.loli.net/2022/09/08/J2jXpQHteShG7N9.png)

1.首先选择一个公共github仓库来存储评论，可以直接用你现在的个人仓库username.github.io，或者你可以新建一个仓库来存储评论。别人在你的文章下面评论时，会在这个仓库的issue里生成对应的评论。

2.然后如果没有申请过Github Application，这里需要先申请一个[Github Application](https://github.com/settings/applications/new)，申请页面中的各项内容已在图中进行了说明，**一定要注意Homepage URL和Authorization callback URL两个URL的填写。**

![图片26.png](https://s2.loli.net/2022/09/08/mSyCO6xJ29uYqPo.png)

3.申请Github Application后，会跳转到这个界面，然后新建一个Client secrets。**注意，一定要记录这个Client secrets，页面刷新后就会变成图中的形式，隐藏起来**。owner是你的用户名，repo是你存储评论的仓库名，可以是个人仓库或者新建一个仓库，admin可以空着。然后将owner、repo、Client ID和Client secrets输入到_config.yml文件的对应位置中，就可以在你的文章下面进行评论了。

![图片35.png](https://s2.loli.net/2022/09/08/rDgKGt63H2fj1oE.png)

![图片27.png](https://s2.loli.net/2022/09/08/tDperbfUgzi2AR1.png)

4.到这一步，主题的基本配置已经配置好了。个人主页如下图所示，下面将介绍如何在主页上添加自己的内容。

![图片28.png](https://s2.loli.net/2022/09/08/9XRHJyCNSMoKLcQ.png)

### 往主页添加内容（VS Code或者typora）

**添加的内容都是.md文件的形式。** 这是是通过VS Code来写markdown文件，有关markdown的语法可以参考[链接](https://yuxiangtiant.github.io/2022/09/08/markdown/)。

在仓库的本地文件中，添加的内容主要与 **_posts、_drafts和_wiki** 这三个文件夹有关。

#### _posts和_drafts文件夹

_posts文件夹中是已发布的博客文章，_drafts文件夹中是尚未发布的博客文章。这两个文件夹的 **.md文件命名格式：年-月-日-文章名** ，例如，2022-09-08-操作说明。博客文章的模板是一样的，下面是文章模板的说明：

1.layout是发布的位置。这里是发布在首页，对应的是post。

2.title是文章的标题。

3.categories是文章的标签。可以是一个或者多个标签。在发布一篇文章后，如果标签是第一次出现，在标签列表会自动生成标签。并且在分类页面的标签列表也会自动生成标签，文章会自动归类。

4.description是文章的描述。

5.keywords是文章的关键字。

6.文章内容。

![图片29.png](https://s2.loli.net/2022/09/08/VrSsuQ58qLlivIT.png)

#### _wiki文件夹

_wiki文件夹中是已发布的wiki页面。**.md文件命名格式：一级标签-<二级标签-> 文章名** ,例如，Android-文章名是一级标签，而Android-Tools-文章名是一级标签和二级标签。下面是页面模板的说明：

1.layout是发布的位置。这里是发布在维基，对应的是wiki。

2.title是文章的标题。

3.cate1是文章的一级标签。

4.cate2是文章的二级标签。

5.description是文章的描述。

6.keywords是文章的关键字。

7.文章内容。

![图片30.png](https://s2.loli.net/2022/09/08/Mml6Z5dPxkBbQ7W.png)

### 修改「关于」页面

pages/about.md文件内容对应网站的「关于」页面，里面的内容多为个人相关信息，将它们替换成你自己的信息，包括_data目录下的skills.yml和social.yml文件里的数据。

1.在pages/about.md文件里修改个人描述。

![图片31.png](https://s2.loli.net/2022/09/08/gsaG5RWQ4E213dM.png)

2.在skills.yml文件里修改你会的技能。

![图片32.png](https://s2.loli.net/2022/09/08/qJpv9VODgtuWmrT.png)

3.在social.yml文件里修改你的相关链接和友情链接。

![图片33.png](https://s2.loli.net/2022/09/08/mpGh4iKCFx9PeXg.png)

### 修改「链接」页面

修改_data目录下的links.yml文件里的数据。

![图片34.png](https://s2.loli.net/2022/09/08/l9EGIu3fkBpvtOM.png)
