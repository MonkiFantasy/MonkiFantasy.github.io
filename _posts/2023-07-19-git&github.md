---
layout: article
tags: git|github
title: "Git&Github相关指令"
---

## 修改git用户

```bash
git config --global user.email "MonkiFantasy@outlook.com"
git config --global user.name "MonkiFantasy"
```

## 个人向查看git log方式

```bash
 git log --all --graph --decorate --oneline
```

## git checkout 用法

1. 根据哈希码查看详细信息

```bash
git checkout cc30c4b
```

2. 切换分支

```bash
git checkout master
```

## github 解决push相关问题（玄学）

```bash
git config --global --unset http.proxy
git config --global --unset https.proxy
```

```cmd
ipconfig/flushdns
```

