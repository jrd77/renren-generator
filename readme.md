##代码生成工具
来自码云:https://gitee.com/renrenio/renren-security/tree/master/renren-generator

**经常需要修改的就是 renren-generator\src\main\resources\template下面的各种生成模板
      配置包名,jdbc类型,忽略前缀等在renren-generator\src\main\resources\generator.properties
      按需修改**

>适用于智慧服务区或其他springboot+shiro+小程序项目
如果需要修改模板
    
    ├─renren-generator  代码生成器
    │        └─resources 
    │           ├─mapper   MyBatis文件
    │           ├─template 代码生成器模板（可增加或修改相应模板）
    │           ├─application.yml    全局配置文件
    │           └─generator.properties   代码生成器，配置文件

