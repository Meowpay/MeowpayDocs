
## 步骤
<a href="https://meowpay.org" target="_blank" >注册账号</a> ->升级为商业用户 ->获取APP配额 ->添加APP ->输入信息 ->使用交互脚本安装

``` bash
bash <(curl -sfSL https://raw.githubusercontent.com/Meowpay/MeowpayDocs/main/install.sh)
```


安装完毕后打开管理后台，配置 ->支付配置 ->找到MeowPay ->编辑 ->商户ID一栏输入appID ->商户密钥一栏输入appID ->支付标识填Monero -> 支付方式填跳转 ->支付处理路由 /pay/meowpay ->启用 

## 补充说明

notify_url 为 https://您的网站地址/pay/meowpay/notify_url

**请务必使用HTTPS加密协议**

任何疑问请<a herf="https://t.me/MeowpayChannel" target="_blank" >联系我们</a>