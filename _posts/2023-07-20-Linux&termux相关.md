---
type: article
tag: termux linux 
title: Linux&termux使用相关
---

---
## Introduction

​	本篇笔记用于记录Linux相关指令及相关应用...

---
## Termux与Android互相访问文件方式

1. termux访问android

```shell
termux-setup-storage
```

2. anroid访问termux

​				使用mt管理器，左侧边栏，添加本地存储

---
## SSH连接Termux



---



```sh
ssh ip -p 8022 #termux使用的是8022端口
```

***注：***vmware虚拟机网络使用桥接模式后，在同一局域网下，也能与termux进行ssh连接



