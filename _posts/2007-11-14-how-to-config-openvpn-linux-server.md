# OPENVPN 内网穿透

通常情况下，研发主机都在内网，经常会有一些远程跨公网的访问需求，以往的做法是在路由器上映射端口，相对来说不够安全。
此时vpn可以构建虚拟局域网，作为内网穿透非常好用。

> 清单
- 一台服务器或ECS
- OPEN vpn-server & vpn-client
- 一键安装

## 一台服务器或ECS

我部署试用了阿里云的ECS,open-vpn的默认配置端口是1194/udp,注意一点可能需要在阿里云ECS安全组里添加白名单。

## OPEN vpn-server & vpn-client

https://www.digitalocean.com/community/tutorials/how-to-set-up-an-openvpn-server-on-ubuntu-16-04
一步步来回折腾估计也得个大半天。

## 一键安装

```
wget https://git.io/vpn -O openvpn-install.sh && bash openvpn-install.sh
```

## 其他