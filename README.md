# Android-cxpc
基于Android平台的出行拼车软件；Ride-sharing software based on Android platform


前言：
随着城市化的进程，交通拥堵越来越严重，出行成本也越来越高，拼车成为了一种受欢迎的出行方式。本项目旨在开发一款出行拼车软件，方便用户之间互相匹配拼车需求，实现拼车出行，减少交通拥堵，降低出行成本。

开发工具：
本项目采用Java语言开发，使用Spring Boot框架，前端采用React技术。数据库使用MySQL，通过MyBatis框架与应用程序进行交互。项目管理采用Maven，版本控制使用Git。

功能模块：

用户注册登录：用户可以通过手机号、微信等方式进行注册登录。
拼车发布：用户可以发布拼车需求，包括出发地、目的地、出行时间等信息。
拼车搜索：用户可以根据自己的出发地、目的地、出行时间等信息进行搜索匹配。
拼车匹配：系统根据用户发布的信息进行匹配，匹配成功后会提示用户，并提供联系方式。
订单管理：用户可以查看自己发布的订单信息，管理自己的订单状态等。
评价系统：用户可以对完成的拼车订单进行评价，评价内容包括安全、舒适度、整体体验等。
运行步骤：

克隆代码：将代码克隆到本地，使用IDEA等工具打开项目。
数据库配置：在MySQL中创建名为"carpool"的数据库，配置数据库连接信息。
运行项目：在IDEA中运行项目，访问http://localhost:8080即可。
关于：
本项目旨在为用户提供方便快捷的出行拼车服务，让用户可以通过拼车的方式减少交通拥堵，降低出行成本。同时，本项目也是一个不断迭代优化的开源项目，欢迎有兴趣的开发者一起参与贡献。