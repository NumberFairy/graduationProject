郑航校友网使用说明：
1、安装JDK1.8，并参照网上经验正确配置环境变量；
		注意：jdk和jre的目录要记得，下面步骤会用到。
2、安装Eclipse，安装完成后参照网上经验下载Jetty插件，安装到Eclipse上；
		注意：Eclipse版本没有明确要求，顺便提一下我用的是Eclipse Neon这个版本；Jetty的版本是		6.1；
3、安装Mysql 5.5.36,安装完成后如果有需要可以安装Navigate客户端；
4、安装mongo数据库，具体方式参照网上方式安装；mongo版本1.00；
5、使用navigate客户端将alumni.sql文件导入到数据库中；
6、使用mongobooster将mongo文件夹中的两个json文件导入到mongo数据库中；
7、在Eclipse中导入alumn项目，并把项目部署到Jetty上，然后运行；
5、打开Google浏览器输入http://localhost:8080即可访问郑航校友网主页；
	注意：我的项目部署到Jetty上用的是8080端口，这个视自己的情况而定。
8、数据库的用户名密码等信息我都在项目的配置文件中写定，如果是通过Windows控制台直接要进入数据库的话，用户名root，密码123；