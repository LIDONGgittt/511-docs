# 实验室服务器使用指南

*有疑问可自行谷歌或询问师兄师姐*

## 系统内已装平台/库/软件版本

（请大家自行维护添加这个列表）

- Ubuntu16.04
- ROS Kinetic
- nvidia 390 + cuda 8.0 + cudnn 6.0

## 登录说明

- 账号说明：每个人的账号名为名字缩写加姓氏全拼，如zydu(杜卓洋)，初始密码为12345，可自行更改。
- 远程登录： 通过命令行ssh远程登陆到服务器，例如 ssh user@10.15.90.168，其中user是用户名。
- 关于vpn：
    - 可以直接上内网，外网的上网教程可参考：https://blog.csdn.net/qq_19260887/article/details/76662816#2vpn%E5%AE%A2%E6%88%B7%E7%AB%AF%E8%BF%9E%E6%8E%A5
    - vpn-connect已安装，可直接 sudo vpn-connect 连外网， sudo vpn-connect -c 可配置用户名密码。

## 使用规范

- 请大家及时做好代码备份，推荐使用git管理代码。
- 需要运行深度学习代码的同学请在anaconda中配置自己的python环境。
- 安装某些软件包或者依赖时请注意有没有和原先系统发生冲突。

