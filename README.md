
    
**简要描述：** 

-根据累计时长算出等级一级等级对应的图标。

**图片**
![](https://www.showdoc.cc/server/api/common/visitfile/sign/a34488f301fa031df3a59b9de75c68ca?showdoc=.jpg)
![](https://www.showdoc.cc/server/api/common/visitfile/sign/15b9b1da2da91cd883c1f81ecb9bc6b5?showdoc=.jpg)
![](https://www.showdoc.cc/server/api/common/visitfile/sign/2c8ffde656a84c59eaabf3afe7f21e2f?showdoc=.jpg)
![](https://www.showdoc.cc/server/api/common/visitfile/sign/b88d3563e88d2e09048e2f38d02a3262?showdoc=.jpg)
![](https://www.showdoc.cc/server/api/common/visitfile/sign/f8fd961f821beae845ebbd9f0e1e17c6?showdoc=.jpg)

**使用方法**

`先引入 qqLevel.js

先通过总的在线时长（秒）计算等级：

var level = qqLevel.getLevel(总秒数，2);

第二个参数为2小时算一天。如果8小时则写8

var img = qqLevel.getImg(level,[
		'图片地址1为0等级图片',
		'图片地址2为星星图片',
		'图片地址3为月亮图片',
		'图片地址4为太阳图片',
		'图片地址5为皇冠图片',
])`

调用结果：
![](https://www.showdoc.cc/server/api/common/visitfile/sign/4822e5105160d1f3f211a0e9d8260a0b?showdoc=.jpg)
