#烟雨蒙蒙（这名有点土）
###注意事项：
	1.数据库文件在yymm.sql里面，需要导入后使用。
	2.联系我发送页面的发送邮件邮箱密码需要自行填上，邮件发送使用了SAE的saemail函数，本地测试需要修改。
	3.作品使用了wordpress二次开发，wordpress管理页面在./ytu/wp_admin进入，管理用户名autumn密码123456.
	4.因作品使用了云服务，测试时需要连接网络。
	5.本作品已经在网络上部署，查看可以访问http://yymm.fddcn.cn/
    6.目录下的config/config.php文件需要自己修改数据库密码，ytu/wp-config.php也需要修改。
###作品说明：
	烟雨蒙蒙是一款用户在线的照片分享平台:
    1.在分享照片页面上传照片后可以展现在首页，
    2.大片模式，提供照片的优化服务，类似于‘足迹’的大片模式，可以实现‘足迹’的功能，
    3.照片墙，实现照片的瀑布流加载。
    4.烟大新闻模块是资讯模块，可以实现文章的发布删除。
    5.联系我模块实现的在线的邮件发送。
###更新日志
1.新增随机台词。  
2.修复台词中有英文时，图片生成失败的BUG.    
3.照片墙新增预览。
###安装帮助
1. 修改config/config.php(连接数据库哒！)。
2. 修改ytu/wp-config.php(也是连接数据库哒！)。
3. 修改php/mail.php里面的接收邮件和发送邮件的地址和密码，用于联系我页面。
4. 使用了百度翻译，需要到[http://developer.baidu.com/](http://developer.baidu.com/)申请一个appkey。
5. 使用了新浪运储存，需要到[http://open.sinastorage.com/](http://open.sinastorage.com/)申请AccessKey和SecretKey并创建一个Bucket。并修改big.php和share/upload/upload.php中相关内容。