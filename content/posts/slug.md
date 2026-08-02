---
title: 测试slug的作用
date: 2026-08-02T09:07:39+08:00
draft: false
tags:
  - 测试
categories:
  - 学习
description: 仅作为测试，后续删除
slug: testslug
---

# 这是一个slug测试

核心规则与效果

- **覆盖默认路径**：如果不写 `slug`，Hugo 默认会用 `title` 或文件名生成 URL。写了之后，URL 末尾就会变成指定的 `slug` 值。

- **SEO 友好**：长标题或中文标题会导致 URL 过长或乱码，使用简洁的英文 `slug`（如 `braised-pork`）可以让链接更美观、利于搜索。

- **模板调用**：在主题模板中，可以通过 `{{ .Slug }}` 获取该值。

![北京大观园](https://img.engout.win/202608/202608020910009.jpg)