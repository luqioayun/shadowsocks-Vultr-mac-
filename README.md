# Shadowsocks-Vultr-Mac
## 构建一个科学上网（翻墙）方式
### 0.原理参考链接
包括socks协议，代理服务器等。
<br>https://www.bilibili.com/video/BV1JA411u7mZ/?spm_id_from=autoNext&vd_source=38425f27a1de84f18208286c823432fc
<br>https://github.com/w910820618/shadowsocks
<br>https://github.com/shadowsocksrr/
<br>https://github.com/frank-lam/vps-ss?tab=readme-ov-file
### 1、vps服务器
#### 1.1注册vultr账号以及充值
Vultr注册新账号&一些优惠（白嫖）活动：
<br>1）活动链接：https://www.vultrcn.com/11.html
<br>2）退款： https://www.56dr.com/info/43311.html
#### 1.2给服务器充值
1）新用户注册赠送活动：新的IP，新的账号，点特定的链接，需要充至少5$激活（https://www.vultrcn.com/11.html）。
<br>2）新用户充值充多少送多少，上限100$：新账号，从来没充过值，优惠码（https://www.vultrcn.com/11.html）。
<br>3）直接充值。
<br>一些赠送活动的充值激活只支持部分付款方式，visa、银联unionpay信用卡、PayPal，支付宝不支持。
#### 1.3部署服务器
1）部署socks服务
<br>亲测有效的参考链接：https://github.com/moraaah/Vultr-Shadowsocks
<br>centos7*64系统似乎有问题，无法使用yum install 命令，会报错14: curl#6 - "Could not resolve host: mirrorlist.centos.org; 未知的错误"
<br>2）启动BBR加速上网：参考链接https://github.com/wenliuaurora/vpn
### 2、Shadowsocks客户端配置
