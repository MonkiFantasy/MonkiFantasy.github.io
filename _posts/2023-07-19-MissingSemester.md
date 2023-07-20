---
type: article
tags: bilibili missing-semester
title: Missing-Semester
---

# Missing-Semester 视频+笔记

## 第1讲 - 课程概览与 shell

<div>{%- include extensions/bilibili.html id='271280711' -%}</div>
``` shell 
cd - #与上一路径切换
which 程序名 #查看运行的程序路径
< > #输入输出重定向
pa a| pb b #管道左边程序输出作为右边程序输入
tail -n5 文件名 #文件尾5行
head -n5 文件名 #文件头5行
grep 字符串 文件名 #查找文件中所有字符串
```

## 第2讲 - Shell 工具和脚本

<div>{%- include extensions/bilibili.html id='656384215' -%}</div>
```shell
a=b #变量定义 
echo $a   #结果为b
！！ #代表上一条命令
$?  #查看错误代码
\#! shebang   #当前脚本运行环境
bash脚本中 $0为脚本文件$1-n为脚本参数名
$#为参数数量 $$为进程id（ pid ）$@为参数列表
find / -name "" -type 类型 #文件查找
tree #打印目录结构
```

## 第3讲 - 编辑器 (Vim)

<div>{%- include extensions/bilibili.html id='868921838' -%}</div>

```vim
:sp 打开同一个文件
^ 移动光标到当前行第一个非空字符
CTRL U 
CTRL D
G 文档底部
gg 文档顶部
e当前单词末尾/end
L 当前屏幕显示最低行/low
M 当前屏幕显示中间/mediu
H 当前屏幕显示顶部/height
f+字符 查找光标跳转到当前行光标后第一个该字符/find
F+字符 查找光标跳转到当前行光标前第一个该字符
t+字符 查找光标跳转到当前行光标后第一个该字符的前一个字符/to
T+字符 查找光标跳转到当前行光标前第一个该字符的后一个字符
d配合移动使用/delete
c配合移动使用/change 会进入插入模式
x删除光标所在字符
r用下一个输入的字符替换当前光标所在字符/replace
u/undo
Ctrl+R/redo
y/yank
yw yy 
VIEW MODE
~ 反转大小写
ci[/change in []  删除[]内内容并进入插入模式
da( 删除完整的包括括号的分组
% 光标在括号两端来回跳转
/ 表示search 要跳转查找到的下一个用n,跳转到上一个用N
.重复执行前一个编辑指令
```



## 第4讲 - 数据整理

<div>{%- include extensions/bilibili.html id='529118338' -%}</div>

## 第5讲 - 命令行环境

<div>{%- include extensions/bilibili.html id='656647234' -%}</div>
```shell
tmux new -s name #创建会话
tmux a -t name #打开会话
ctrl +b后按以下键

+ d #deteach后台挂起tmux

+ " #水平分屏tap

+ % #垂直分屏tap

+ space #均匀分配分屏的空间

ctrl + d #退出且不保留会话
```

## 第6讲 - 版本控制(Git)

<div>{%- include extensions/bilibili.html id='614243433' -%}</div>
[Git&Github相关指令 - Monki's blog (monkifantasy.github.io)](https://monkifantasy.github.io/2023/07/19/git&github.html)

## 第7讲 - 调试及性能分析

<div>{%- include extensions/bilibili.html id='614191382' -%}</div>

## 第8讲 - 元编程

<div>{%- include extensions/bilibili.html id='401840166' -%}</div>

## 第9讲 - 安全和密码学

<div>{%- include extensions/bilibili.html id='314297208' -%}</div>

## 第10讲 - 大杂烩

<div>{%- include extensions/bilibili.html id='271770049' -%}</div>

## 第11讲 - 提问&回答

<div>{%- include extensions/bilibili.html id='314291946' -%}</div>

