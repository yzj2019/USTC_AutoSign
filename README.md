# USTC每日健康上报自动化

#### 开机自启动服务

https://blog.csdn.net/superjunenaruto/article/details/105890739

#### 通过统一身份认证连接综合教务系统，并保持连接

1. 使用requests方法实现，https://blog.csdn.net/xc_zhou/article/details/81021496?utm_medium=distribute.pc_relevant_t0.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-1.control&dist_request_id=&depth_1-utm_source=distribute.pc_relevant_t0.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-1.control，https://blog.csdn.net/qq_37616069/article/details/80376776
2. 统一身份认证+动态页面爬取https://www.jianshu.com/p/8cd6e9bc2680，先chrome开发者工具分析登录过程，再进行模仿
3. 也可考虑使用webdriver实现，见https://blog.csdn.net/Haven200/article/details/103208795

#### 自动打卡功能开发（已经绕过统一身份认证）

同见https://www.jianshu.com/p/8cd6e9bc2680