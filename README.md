#[JFinal](http://www.jfinal.com/)框架

>####主要特点

- MVC架构，设计精巧，使用简单；
- 遵循COC原则，零配置，无xml；
- ActiveRecord支持，使数据库开发极致快速；
- 自动加载修改后的java文件，开发过程中无需重启Web server；
- AOP支持，拦截器配置灵活，功能强大；
- Plugin体系结构，扩展性强；
- 多视图支持，支持FreeMarker、JSP、Velocity；
- 强大的Validator后端校验功能；
- 功能齐全，拥有Struts2的绝大部分功能；
- 体积小仅180K，且无第三方依赖。

>####设计思想

- 微内核+全方位扩展架构；
- Db + Record 模式；
- CPI模式；
- ActiveRecord模式Java实现方式；
- API引导式配置；
- API引导Validate；
- 采用Scanner + ClassLoader结合Jetty实现热加载；
- 极简设计，核心代码约2000行实现Web MVC + ORM。

>####架构原理

![](http://cms.csdnimg.cn/article/201312/10/52a67b9259de2.jpg)

