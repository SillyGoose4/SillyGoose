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
  + 服务端为 __Java Servlet__ 程序，采用 __SpringBoot + Mybatis3__ 框架，数据库为MySQL 5.7，使用 __maven__ 管理包，详情见[服务端链接](https://github.com/SillyGoose4/SillyGooseServerSpringBoot)
---
  + 客户端为 __Android__ 程序，采用 __OkHttp3__ 框架进行http连接，图片加载库为 __Universal-Image-Loader__ ，天气服务使用的是__易源数据__([ShowAPI](https://www.showapi.com/))，可以说是一个大杂烩了，参照网上的代码自建了很多没用的轮子（为了学习嘛），详情见[客户端链接](https://github.com/SillyGoose4/Client)客户端有很大缺陷，暂未完工

### Build

1.获取源码
首先应clone项目至本地计算机  

    git clone https://github.com/SillyGoose4/SillyGooseServerSpringBoot.git Server
    git clone https://github.com/SillyGoose4/Client.git Client

2.导入项目  
如果你使用 __IDEA__ 和 __Android Studio__ ,只需要导入静待自动运行结束即可  
如果使用 __eclipse__ ，则先需要安装 __maven__ ，然后用maven download 下载jar包，下载完即可运行

3.启动  


### RELEASE
[客户端](https://github.com/SillyGoose4/Client/raw/master/app/build/outputs/apk/release/%E9%80%9B%E5%90%83%E7%9A%84%E9%B9%851.0.9.apk)  
服务端我们已部署至阿里云服务器（阿里云的学生机，带宽只有1Mbps），可直接使用也可自行配置。


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
推荐使用 _IDEA_ 和 _Android Studio_
