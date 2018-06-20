# SillyGoose
Android小游戏 逛吃的鹅
### Description
  + 一个以收集实时天气、转换为鹅民币去旅行的收集类游戏
    本来是打算模仿旅行青蛙做个佛系游戏，然鹅没脑洞，没有好的游戏性，后期可提升性不大，主要是用来学习
  + bug贼多，美工不是专业的，程序员也不是专业的，凑活看吧
  + 时间不是特别充裕，技术水平落后，现在只上线了第一版（In 19/6/2018）
  +
---
  + 完整的项目包括两大部分：服务端和客户端，项目附赠设计文档、数据库文档等内容，这是一个完整的网络简易收集类游戏构建项目。
---
  + 服务端为 __Java Servlet__ 程序，采用 __SpringBoot + Mybatis3__ 框架，数据库为MySQL 5.7，使用__maven__管理包，详情见[服务端链接](https://github.com/SillyGoose4/SillyGooseServerSpringBoot)
---
  + 客户端为 __Android__ 程序，采用__OkHttp3__框架进行http连接，图片加载库为__Universal-Image-Loader__，天气服务使用的是__易源数据__([ShowAPI](https://www.showapi.com/))，可以说是一个大杂烩了，参照网上的代码自建了很多没用的轮子（为了学习嘛），详情见[客户端链接](https://github.com/SillyGoose4/Client)

### Build

1.获取源码
首先应clone项目至本地计算机  

    git clone https://github.com/SillyGoose4/SillyGooseServerSpringBoot.git Server
    git clone https://github.com/SillyGoose4/Client.git Client

2.导入项目至IDE  
如果你使用__IDEA__和__Android Studio__,只需要导入静待自动运行结束即可  
如果使用eclipse，则先需要安装maven，然后用maven download 下载jar包，下载完即可运行


### RELEASE


### Contributor  
* [王家若](http://github.com/wjr22)
* 杜雨雯
* 杨国雪莹
* 朱晓悦
(排名不分先后)  

### LICENSE
we used [`GNU General Public License v3.0`](/SillyGoose/LICENSE) LICENSE
### Contact Us
我们是在校学生！欢迎联系！  
小组Email    ： SillyGoose4@163.com  
个人Email(推荐)   : wangjiaruo22@hotmail.com  
__欢迎提出意见和建议！__
__欢迎fork！欢迎Star！欢迎Push！__
##### Explain:
1.  
2.推荐使用_IDEA_和_Android Studio_
