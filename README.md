# magazine
Selling magazine

# 项目配置
1.数据库配置：
(1)新建数据库magazine,新建用户leon/Leon2014,并授权该用户对数据有完全控制.
(2)使用mysql客户端导入/src/main/webapp/sql/magazine.sql
2.Tomcat配置:
(1)修改/conf/server.xml,在host标签下增加上传目录的配置:
	<Context docBase="c:\upload" path="/magazine/upload/" reloadable="true" />
(2)
