# magazine
杂志商城网站

# 项目配置

## 数据库配置
1. 新建数据库magazine,新建用户leon/Leon2014,并授权该用户对数据有完全控制.
2. 使用mysql客户端导入/src/main/webapp/sql/magazine.sql

## Tomcat配置
1. 修改/conf/server.xml,在host标签下增加上传目录的配置
`<Context docBase="c:\upload" path="/magazine/upload/" reloadable="true" />`

## BUG跟踪
- 首页点击文章标题无法打开文章详情
- 查找商品页面的结果，点开报404


## 待实施项

