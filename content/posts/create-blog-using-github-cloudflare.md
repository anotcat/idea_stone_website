+++
title = '使用 Github + Cloudflare 部署自己的博客'
weight = 1
aliases = ["/create-blog-using-github-cloudflare"]

summary = ""
date = 2024-05-23T17:48:05+08:00
tags = ["技术"]
draft = false
+++

> 之前使用过 Github Page，博客也没有坚持下去，属于建完就走的类型，这次换新体验下“赛博菩萨”——Cloudflare。希望菩萨保佑能够更新下去。聊胜于无。
## 一、需要的软件及账号
1. 需要安装 git 并且有 Github 账号；
2. 注册 Cloudflare 账号。
## 二、配置 Hugo 
> 雨果，名字听起来果然是有文化。官网有很详细的配置教程，先动起来。
> [查看 *hugo 配置指南*。 ](https://developers.cloudflare.com/pages/framework-guides/deploy-a-hugo-site/)

## 三、Github 创建一个仓库
> 这个与之前使用 Github Page 不一样，使用 Cloudflare,创建公开或者私有仓库都可以，后续配置 Cloudflare 会授权访问。

> 记得可以给仓库取个**好听的名字**，随意。
> [创建Github仓库。](https://developers.cloudflare.com/pages/framework-guides/deploy-a-hugo-site/#create-a-github-repository)

## 四、配置 Cloudflare 
> [查看 *cloudflare pages 配置指南*。](https://developers.cloudflare.com/pages/framework-guides/deploy-a-hugo-site/#deploy-with-cloudflare-pages)

## 五、自定义一些配置
1. 网站图标 favicon
```

```
2. 页脚注释
```html
<!--

位置：themes/paper/layouts/partials/footer.html

修改：-->

<span>
        Powered by
        <a href="https://gohugo.io/" rel="noopener noreferrer" target="_blank">Hugo</a> &
        <a href="https://github.com/adityatelange/hugo-PaperMod/" rel="noopener" target="_blank">PaperMod</a>
</span> 
```
