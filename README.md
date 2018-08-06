# PythonSpider
基于Python3.7的简单的爬虫Demo,包含爬取百度百科,51job北京java岗位的招聘信息,并把爬取内容保存在MySQL数据库中

## 开发环境及项目框架介绍
- IDE:Intellij IDEA
- 数据库:MySQL 
(保存百度百科数据的数据库结构代码[baike.sql](https://github.com/suxiongwei/PythonSpider/blob/master/baike.sql))
(保存51job数据的数据库结构代码[baike.sql](https://github.com/suxiongwei/PythonSpider/blob/master/java.sql))
- 代码管理:Git

## 模块介绍
- url_manager.py:URL管理器
- html_downloader.py: 网页下载器（urllib2）
- html_parser.py:网页解析器（BeautifulSoup）
- html_outputer:输出爬取数据
## 演示步骤
- 爬取百度百科数据:运行spider_main.py
- 51job北京java岗位的招聘信息:运行51job.py
