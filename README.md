# 项目模块介绍

* shiro模块为Springboot + Shiro + Redis实现分布式权限管理

* shiro_jwt模块为Spring + Shiro + JWT实现无状态鉴权机制(token)


# 相关问题

* 使用redis实现session管理 https://blog.csdn.net/baidu_33969289/article/details/84843828

* 使用redis实现cache管理 https://blog.csdn.net/baidu_33969289/article/details/86670054

* shiro整合JWT https://blog.csdn.net/baidu_33969289/article/details/86616058

* 集成kaptcha验证码 https://blog.csdn.net/baidu_33969289/article/details/87473766

* 实现帐号登录人数控制 https://blog.csdn.net/baidu_33969289/article/details/87740294


* sql.text为数据库表结构






baidu_33969289
baidu_339692898个月前#16楼
https://github.com/gemingyi/shiro_demo 参考代码
举报回复收起回复
wozniakzhang
长草颜团子-张晓祥回复 baidu_339692894个月前
可以自定义时间的,如果配置了全局拦截器,但是拦截不到,报错getWriter() has already been called for this response 请参考https://blog.csdn.net/wozniakzhang/article/details/95855296
