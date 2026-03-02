---
title: "Git命令"
subtitle: ""
date: '2025-06-24T13:09:00+08:00'
lastmod: '2026-01-27T11:01:00+08:00'
draft: false
categories: ['学习']
tags: ['Git','命令']
---



### 子模块

添加子模块
```shell
git submodule add child_module_url
```

主仓库和子模块仓库同时拉取

```shell
git clone --recurse-submodules repo-url
```

若主仓库已经拉取，单独拉取子模块

```shell
git submodule update --recursive
```
