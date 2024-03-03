# frpc
## 项目简介
基于 [fatedier/frp](https://github.com/fatedier/frp) 原版 frp 内网穿透客户端 frpc 的一键安装卸载脚本Linux等多种环境安装部署.

- Fork by GitHub [stilleshan/frpc](https://github.com/stilleshan/frpc)

### Linux 服务器 一键脚本安装
> *本脚本目前同时支持 Linux X86 和 ARM 架构*

安装
```shell
wget https://raw.githubusercontent.com/wjqserver/frpc/master/frpc_linux_install.sh && chmod +x frpc_linux_install.sh && ./frpc_linux_install.sh
# 以下为国内镜像
wget https://tools.wjqserver.xyz/https://raw.githubusercontent.com/wjqserver/frpc/master/frpc_linux_install.sh && chmod +x frpc_linux_install.sh && ./frpc_linux_install.sh
```

使用
```shell
vi /usr/local/frp/frpc.ini
# 修改 frpc.ini 配置
sudo systemctl restart frpc
# 重启 frpc 服务即可生效
```
