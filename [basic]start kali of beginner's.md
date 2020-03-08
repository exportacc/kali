---
layout:     post
title:      [basic]start kali of beginner's 
subtitle:   初學者要學會的基本指令和動作
date:       2020-03-08
author:     GEo
header-img: img/post.jpg
catalog: true
tags:
    - 
---

## broke root password

> Kali linux 2019 版本不適用

> 只適用 2020.1 

一開始按 e 

到 kali linux 處 把 ro 後面全部砍掉 並把 ro 改成 rw 并在後面加上一串指令

```
rw initrd=/install/initrd.gz init=/bin/bash
```

F10 

```passwd``` 更改password 

exec /sbin/init

## package update

apt 

> 高級套件工具 

> Advanced Packaging Tool

```
apt-get update
```
重新同步本地軟體包 , 這個更新套件的第一步

```
apt-get upgrade
```
把同步后的軟體包,安裝 。 

## add user noroot

```
adduser <name>
```
