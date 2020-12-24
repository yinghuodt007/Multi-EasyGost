# Multi-EasyGost一键脚本使用指南
***
## 感谢: 
1. 感谢 @ginuerzh 大佬提供了如此优秀实用的软件，项目地址 `https://github.com/ginuerzh/gost` ，GOST功能强大使用简单，想要详细了解用法的朋友可以查看官方文档 `https://docs.ginuerzh.xyz/gost/`  
2. 感谢 @风萧萧兮易水寒 大佬的原始脚本，项目地址`https://www.fiisi.com/?p=125` 
3. 感谢 @ STSDUST 提供的EasyGost脚本（已删库），此脚本是基于其进行修改增强
***
## 简介

> 项目地址及帮助文档:  
> https://github.com/KANIKIG/Multi-EasyGost
***
## 脚本

* 启动脚本  
  `wget --no-check-certificate -O gost.sh https://raw.githubusercontent.com/yinghuodt007/Multi-EasyGost/master/gost.sh && chmod +x gost.sh && ./gost.sh`  
* 再次运行本脚本只需要输入`./gost.sh`回车即可  

## 功能

### 原脚本功能

- 实现了systemd及gost配置文件对gost进行管理
- 在不借助其他工具(如screen)的情况下实现多条转发规则同时生效
- 机器reboot后转发不失效
- 支持传输类型：
  - tcp+udp不加密转发
  -  relay+tls加密

### 此脚本新增功能

- 增加了传输类型选择功能
- 新支持传输类型
  - relay+ws
  - relay+wss

- 落地机一键创建ss或socks5代理 (gost内置)

## 功能展示

![1](https://i.loli.net/2020/10/16/pZSQqlXyYmJEnt1.png)

![2](https://i.loli.net/2020/10/16/fBHgwStVQxc821z.png)

![3](https://i.loli.net/2020/10/16/xgZ6eVAwSzDUFjO.png)

![4](https://i.loli.net/2020/10/16/lt6uAzI5X7yYWhr.png)
