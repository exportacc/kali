---
layout:     post
title:      [basic]Install Jupyter In Kali Linux
subtitle:   How to install Jupyter Notebook
date:       2020-03-07
author:     GEo
catalog: true
tags:
    - Kali Linux
---

我是建立一個虛擬環境再在裏面install Jupyter  

``` pip install virtualenv ```

``` mkdir python-virtual-environments && cd python-virtual-environments ```

```
# Python 2:
$ virtualenv env 

# Python 3
$ python3 -m venv env

```
env 是虛擬環境的名字

```source env/bin/activate``` 

以後都要統一在這個目錄底下裏才有 activate 

```deactivate``` 不用在特定的目錄底下
