# ShadowsocksR_onekey_shell
适用于glzjin面板ssr后端的一键安装脚本 实现输入配置信息、以及全自动安装，支持 modwebapi 及 glzjinmod（mysql connect）
支持 ubuntu14.04+ / centos6+ /debian7+ 
默认安装目录：/root/shadowsocks
```
git clone https://github.com/JiangTx/SSR-manyuser_glzjin_shell.git SSR
cd SSR
bash shadowsocks.sh

设置完后进入安装目录 默认/root/shadowsocks 运行即可
```
安装完成

输入交互比较水，也没有详细判定，不过能用即可，有功夫再完善，没那么多时间造自行车哈
有问题可以提issue，看到了会及时回复并尝试修复问题

# 更新
## version 2.1.2
2017-08-09
调整顺序。优先进行信息输入，然后进入安装流程

## version 2.1.1
2017-07-29

1. libsodium 版本由早期 1.0.10 调整至 1.0.13


## version 2.1

2017-05-07

1.修复因逻辑问题导致配置文件内容异常从而导致的运行报错

2.修复由于 debian 源中有 deb cdrom 而导致的安装中断

### 3.添加了禁用防火墙的相关内容

## version 2.0

2017-05-07

1.实现输入配置信息、以及全自动安装，支持 modwebapi 及 glzjinmod（mysql connect）

2.修复bug

## version 1.1

2017-05-06

1、自动进行相关依赖的安装，支持 ubuntu14.04+ / centos6+ /debian7+ 

