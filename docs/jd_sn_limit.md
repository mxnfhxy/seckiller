JD与SN限制
----

### 京东限制

>   PLUS会员单月 最多购买2瓶，超出限制无法预约，如果超出限制，继续使用脚本刷，可能被风控，请小心对待。

京东会有相似地址、IP、相似身份检测，如果多号，机器硬件、下单信息最好保持孤立，无太大关联性。

### 苏宁限制

>   苏宁新的非Super的且实名过的会员有一定抢购到茅台的概率，这点比京东良心。

但苏宁风控侦测不弱于京东，类似于京东，会有相似地址、IP、相似身份检测，如果多号，机器硬件、下单信息最好保持孤立，无太大关联性。下单时，会有浏览器设备指纹码核验，位置信息上报等。这些通过抓包和它外部 [SDK](https://open.suning.com/ospos/apipage/toDocContent.do?menuId=60) 接口文档可以看出，这也是  `GitHub` 上几乎无苏宁抢购代码原因（很多刷星的垃圾代码）。（当然也是我采用 `Thor` 这种倾入性最小的方式的原因）。

![sn_sdk](sn_sdk.png)

上图来自苏宁官方 [jssdk user guide](http://oss.suning.com/cbpmb/xhsmp/sn/jssdk/0.6.0/USERGUIDE.pdf) 。


>   苏宁每次抢购限购 1 瓶，每个会员正常情况下在30天内能抢到2瓶，如果你最近30天已买到2瓶，建议停止抢购，过个10-15天后再次抢购。