## Alipay-WeChat-HTML
**支付宝和微信的二维码支付页面，包括html和css样式图片等，可用于django等自定义支付页面渲染。自己的django项目用到了接入支付宝微信的功能，然后自己写了个html页面，直接渲染服务接口返回的数据即可（包括金额，二维码等）。**

------------

页面js已经包含了倒计时逻辑，时间可以按照服务接口返回的时间倒计时计算，直接填入时间秒数即可，倒计时结束后则二维码图片替换为过期。
页面还有定时器，每隔两秒执行查询，向服务商发起查询查看是否支付成功，支付成功则将显示支付成功，并且跳转至页面中配制的链接页面上。

------------

**页面具体显示如下：**
支付宝页面
![image](https://github.com/skytotwo/Alipay-WeChat-HTML/raw/master/screencut_alipay.png)

微信页面
![image](https://github.com/skytotwo/Alipay-WeChat-HTML/raw/master/screencut_weixin.png)