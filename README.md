# cordova-youbanban-youmeng
1：插件添加完毕后在app启动后的地方添加如下代码

    // test为生产测试渠道，不影响渠道统计，发布生产包时，改为其它任意值即可。

    MobclickAgent.init("59671c51766613086f001894","test");

2:修改java文件的包名为您的包名即可

