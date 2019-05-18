# 一键安装&升级面板

>以下两条命令皆可，两者是一样的，只需要运行一个，如果其中一个有错误，可以运行另外一个。

>请务必使用 root 用户运行！

```
wget -O /usr/bin/sprov-ui -N --no-check-certificate https://raw.githubusercontent.com/foxbackup/sprov-ui/master/sprov-ui.sh && chmod +x /usr/bin/sprov-ui && sprov-ui

```
提示为找到该命令,那么需要安装：
```
yum install wget
```
# sprov-ui
>一个支持多协议多用户的v2ray Web面板
 
 
# 支持的系统
>务必使用纯净版的系统，建议在 256MB 内存及以上的 vps 搭建，低内存情况下可能运作不良
 - CentOS 7（推荐）
 - Ubuntu 16
 - Ubuntu 18
 - Debian 8
 - Debian 9
Because the author deleted the code, I tried to make a script address with one click.
______________________________________________________________________________
user#:

wget -O /usr/bin/sprov-ui -N --no-check-certificate https://github.com/LuisLIn666/sprov-ui/raw/master/sprov-ui.sh && chmod +x /usr/bin/sprov-ui && sprov-ui

Tested .It can be install on Ubuntu successful.

This script collection BBR,BBR Magic,BBR Plus,Lotserver

If you install TCP Accelerate you must manusal open acceleration

code:
./tcp.sh

You can use   # sysctl net.ipv4.tcp_available_congestion_control   # to see if it‘s started

return "net.ipv4.tcp_available_congestion_control = bbr cubic reno"  or net.ipv4.tcp_available_congestion_control = reno cubic bbr

You can use   # net.ipv4.tcp_congestion_control = bbr   # to see if it‘s started

return net.core.default_qdisc = fq

You can use   #  lsmod | grep bbr # to see if it‘s started

return tcp_bbrplus            20480  8

If any of the above items occur, the startup is successful.
______________________________________
Statement: Anyone who uses this script in illegal ways has nothing to do with me and I am not liable for any major legal responsibility.
