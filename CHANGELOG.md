### v2.4.3 ###
+ celery任务调度[下载书籍图片、发送邮件]
+ 配置文件修改[删除全局配置表]
+ 书籍数据添加latex、

### v2.4.1 ###
+ 客户端书籍数据split优化

### v2.4 ###
+ 日志分割优化[按照midnight分割; error级别日志单独输出]
+ 书籍解析添加对contents->headline->text优化
+ 书籍中的posts有多组文章解析
+ 客户端email添加正则校验
+ 添加后台管理登录界面

### v2.3.3 ###
+ 书籍源文件和输出文件存储目录更改，格式：[主目录/作者/书名标题/书籍大小/]
+ 书籍表SQL更改，增加书籍唯一ID、书籍大小字段(主要是为了防止用户第一次推送为购买的书籍，第二次推送购买过的书籍出现缓存)

### v2.3.2 ###
+ 修复服务端抓取书籍图片bug

### v2.3.1 ###
+ 服务端存储书籍信息，如果存在一样的图书，直接推送
+ 书籍图片多线程抓取
+ 图书章节按照`[class=pagebreak]`分割
+ 客户端CSS优化，不干涉主页面