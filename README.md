# cordova-alipay-base 

Cordova 支付宝基础功能插件

# 功能

仅实现APP的支付宝支付功能

# 安装

0. 背景

本插件来源于 https://github.com/xueron/cordova-alipay-base 


1. 运行

```
cordova plugin add https://github.com/niuniuliuliu/cordova-alipay-base.git --variable APP_ID=your_app_id

```

2. cordova各种衍生命令行都应该支持，例如phonegap或者ionic。

# history
更新安卓使用了最新的支付宝sdk

沙箱环境
import com.alipay.sdk.app.EnvUtils;
EnvUtils.setEnv(EnvUtils.EnvEnum.SANDBOX);

# 许可证

[MIT LICENSE](http://opensource.org/licenses/MIT)
