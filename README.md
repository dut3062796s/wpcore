# wpcore
	World of Warcraft server

	魔兽世界服务器

	运行登录服务器(Run Authserver): php script Server/start auth

	运行世界服务器(Run Worldserver): php script Server/start world

	注: 测试账户(test user) TEST003 密码 TEST003  (数据库密码哈希值加密为: sha1("TEST003:TEST003") )

		创建账户(create user): account create username password

		GM权限(set gmlevel): account set gmlevel username 3 1

		当前核心只能在linux下运行(win版正在兼容中...)

		数据库配置文件是.env，请将.env.example复制到.env并更改配置。

		The database configuration file is in .env, please copy .env.example to .env and change the configuration.

=====

# Introduction
	This is a World of Warcraft server written in php.
	Now it has debugged the process of logging in to the server.
	The current World of Warcraft client is 3.3.5.
	The server list and account password data need to query the auth library.
	The world server is being written...

	The database file is in the root directory: sql/auth.sql

	Limited energy, welcome to submit version, QQ group: 186510932 welcome to learn together ~

	Wow client link: https://pan.baidu.com/s/1A4EeOdngdtIrcgSzfkj6-A extraction code: 2vkt

# 介绍
	这是用php编写的魔兽世界服务器。
	现在它已经调试了登录服务器的过程。
	目前的魔兽世界客户端是3.3.5。
	服务器列表和帐户密码数据需要查询auth库。
	世界服务器正在编写中...

	数据库文件在根目录: sql/auth.sql

	精力有限,欢迎提交版本,QQ群:186510932 欢迎一起研究~

	wow客户端 链接: https://pan.baidu.com/s/1A4EeOdngdtIrcgSzfkj6-A 提取码: 2vkt

~~~
                                                                                 
 PPPP    PPPP     PPP                    PPPPPPP                                 
  PPP    PPPPP    PPP                   PPPPPPPPP                                
  PPPP   PPPPP   PPPP                  PPPP   PPPP                               
  PPPP   PPPPP   PPPP                 PPPP     PPPP                              
   PPP  PPPPPPP  PPP  PPPPPPPP        PPP       PPP   PPPPPP   PPPPPP   PPPPPP   
   PPP  PPP PPP  PPP  PPPPPPPPP      PPPP           PPPPPPPPP  PPPPPP PPPPPPPPP  
   PPPP PPP PPP PPPP  PPPP  PPPP     PPPP           PPPP  PPPP PPPP   PPP   PPPP 
   PPPP PPP PPP PPP   PPP   PPPP     PPPP          PPPP   PPPP PPP   PPPP    PPP 
    PPPPPP  PPPPPPP   PPP    PPP     PPPP          PPP     PPP PPP   PPPPPPPPPPP 
    PPPPPP   PPPPPP   PPP    PPP     PPPP          PPP     PPP PPP   PPPPPPPPPPP 
    PPPPPP   PPPPPP   PPP    PPP      PPP       PPPPPP     PPP PPP   PPP         
     PPPPP   PPPPP    PPP   PPPP      PPPP     PPPPPPPP   PPPP PPP   PPPP        
     PPPP    PPPPP    PPPP  PPPP       PPPP   PPPP  PPPP  PPPP PPP    PPPP  PPPP 
     PPPP     PPPP    PPPPPPPPP         PPPPPPPPPP  PPPPPPPPP  PPP    PPPPPPPPP  
     PPPP     PPPP    PPPPPPPP           PPPPPPP      PPPPPP   PPP      PPPPPP   
                      PPP                                                        
                      PPP                                                        
                      PPP                                                        
                      PPP                                                        
                      PPP 
        
Authserver version 1.0.1
author by.fan <fan3750060@163.com>
Gameversion: 3.3.5

~~~

# 安装及依赖 Installation dependency
	git clone https://github.com/fan3750060/wpcore.git

	Php version >= 7.0
	Swoole version >= 2.0
	Python version >= 3.5

# 运行 Run
	运行登录服务器(Run Authserver): php script Server/start auth

	运行世界服务器(Run Worldserver): php script Server/start world

# Demonstration 演示

![image](https://pictureblog.oss-cn-beijing.aliyuncs.com/wow/0.png?x-oss-process=image/resize,w_1000,h_1000)

![image](https://pictureblog.oss-cn-beijing.aliyuncs.com/wow/1.png?x-oss-process=image/resize,w_1000,h_1000)

![image](https://pictureblog.oss-cn-beijing.aliyuncs.com/wow/2.png?x-oss-process=image/resize,w_1000,h_1000)

![image](https://pictureblog.oss-cn-beijing.aliyuncs.com/wow/3.png?x-oss-process=image/resize,w_1000,h_1000)

![image](https://pictureblog.oss-cn-beijing.aliyuncs.com/wow/4.png?x-oss-process=image/resize,w_1000,h_1000)

![image](https://pictureblog.oss-cn-beijing.aliyuncs.com/wow/5.png?x-oss-process=image/resize,w_1000,h_1000)

![image](https://pictureblog.oss-cn-beijing.aliyuncs.com/wow/6.png?x-oss-process=image/resize,w_1000,h_1000)





	



