# :heart:免费接口

根据各大平台提供的免费接口进行了二次开发，转为无需跨域的免费接口。可用于前端ajax学习，也可以用于实际生产环境。

此接口不断更新中，欢迎 :star: 收藏！

:rainbow:**使用说明：**

1. 根据下面的`api文档`按需复制相应接口地址，并查看接口说明
2. 在前端任意页面、任意项目中，使用任意`ajax`方式（JS的ajax，JQ的ajax, axios,fetch等）获取该接口地址即可。

:warning:**注意：**

​	受数据源平台限制，每日调用次数有限，具体限制请查看接口说明

# :100:API文档

#### 一、jdwx接口

**1、中国和世界全球5万个城市天气预报(每日上限5K次，无需跨域)**

- 接口地址：

  https://api.imqd.cn/jdwx/weather.php

- 请求方式：

  GET

- 请求示例：

  https://api.imqd.cn/jdwx/weather.php?city=changsha

  ↑点击即可看到返回值

- 说明：

  参数`city`默认不填为长沙市天气，支持全球5万个城市（包含中国2567个市县地区）的7天天气预报、实况天气、每3小时天气、AQI空气质量、生活指数等数据！

  city可通过城市中英文名称、ID和IP地址进行，例如`city=北京`，`city=beijing`，`city=CN101010100`，`city= 60.194.130.1`查询的均为北京市天气。

  如果是国外城市，则是该城市的英文名称，比如`city=london`查询的是英国伦敦的天气。

**2、手机号码归属地查询(每日上限1K次，无需跨域)**

- 接口地址：

  https://api.imqd.cn/jdwx/phonelo.php

- 请求方式：

  GET

- 请求示例：

  https://api.imqd.cn/jdwx/phonelo.php?shouji=13988886666 

  ↑点击即可看到返回值

- 说明：

  全国移动、联通、电信等手机号码归属地查询，数据量有数百万，更新及时、准确度高。
  
  参数：`shouji` 手机号必填，为国内11位手机号码。

# :coffee:交个朋友

本接口由WEB前端罗老师开发，我是一位拥有多年web前端开发经验、管理经验、教学经验的实战派全栈工程师。目前在某名企任职WEB前端技术教官。底下加我微信可提供开发、技术咨询、答疑、直播讲座等服务，欢迎进入我的博客了解更多：https://www.imqd.cn/

![wechat](https://image.imqd.cn/wechat.jpg)

> 右边添加我微信一对一免费私聊，拉你加入官方微信答疑群

如果您觉得本项目对您有帮助，也可以请我喝杯咖啡：

![paycode](https://image.imqd.cn/paycode.jpg)
