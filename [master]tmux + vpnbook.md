---
layout:     post
title:      [master] tmux + vpnbook
subtitle:   高效能窗口和高級使用者粉碎文件...
date:       2020-03-08
author:     GEo
header-img: img/post.jpg
catalog: true
tags:
    - kali linux
---

> 高級使用者粉碎文件,使得其沒有復原的機會,提高隱秘性 。

## bleachbit

```
apt-get install bleachbit
```
其功能 : 

    1. 釋放磁盤文件

    2. 刪除 cookie

    3. 消除上網記錄

    4. 粉碎臨時文件

    5. 刪除日志 

```
bleachbit -h 
```

## how to hide my ip address in Kali linux using vpnbook

> 提高隱秘性

google vpnbook

點擊 openVPN 以及 how to do 

點選 ubuntu

```openvpn --config vpnbook... ```

> 備注: 上述的過程都需要建立在沒有開啓vpn的時候

## tmux

```
apt-get tmux
```

```
tmux # start 
```
|  Date   |       Note       | 
|---------|:----------------------------------------------|
|Ctrl+d   |  delete this plane , don't do that !   
|Ctrl+b c |  Create a new window (with shell)
|Ctrl+b w |  Choose window from a list
|Ctrl+b 0 |  Switch to window 0 (by number )
|Ctrl+b , |  Rename the current window
|Ctrl+b % |  Split current pane horizontally into two panes
|Ctrl+b " |  Split current pane vertically into two panes
|Ctrl+b o |  Go to the next pane
|Ctrl+b ; |  Toggle between the current and previous pane
|Ctrl+b x |  Close the current pane

Basic Tmux Usage

Below are the most basic steps for getting started with Tmux:

    1.On the command prompt, type tmux new -s my_session,
    2.Run the desired program.
    3.Use the key sequence Ctrl-b + d to detach from the session.
    4.Reattach to the Tmux session by typing tmux attach-session -t my_session.