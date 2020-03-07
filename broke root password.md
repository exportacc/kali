---
layout:     post
title:      [basic]Broke Root Password   
subtitle:   How to hide my ip address in Kali linux
date:       2020-03-07
author:     GEo
catalog: true
tags:
    - Kali Linux
---

> Kali linux 2019 版本不適用

> 只適用于 2020.1 版本

一開始按 e 

到 kali linux 處 把 ro 後面全部砍掉 並把 ro 改成 rw 并在後面加上一串指令

```
rw initrd=/install/initrd.gz init=/bin/bash
```

F10 

```passwd``` 更改password 

exec /sbin/init
