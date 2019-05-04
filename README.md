Python全球主站网址
http://www.python.org
Python第三方库网址
http://pypi.org
Python计算生态推荐榜
http://python123.io/index/monthly_package


python语言基础：
 1.python3入门，数据类型，字符串
 2.判断/循环语句，函数
 3.类与对象，继承，多态
 4.tkinter界面编程
 5.文件与异常，数据处理简介
 
 
python语言高级：
 1.python常见第三方库与网络编程
 2.面向对象，python正则表达式
 3.求职数据爬虫，金融数据爬虫，多线程爬虫
 4.python MySQL数据库应用，Nosql数据库，spl,jython
 
 
python全栈工程师前端（学会开发前端网页，会使用流行的前端框架）
 1.HTNL+css
 2.网页设计实践
 3.JavaScript+ajax
 4.jquerry
 8.jquerry EasyUI,Mobile简介，photoshop
 6.Bootstrap
 
 
python全栈工程师后端（常用的后端架构）
 1.Django入门
 2.Django高级
 3.django实战
 4.Flask开发原理
 5.Flask开发项目实践
 6.tornado开发原理
 7.tornado开发项目实践
 
 
Linux基础
 1.虚拟机安装
 2.Linux服务器安装与配置
 3.apache服务器与nginx服务器安装与使用
 4.Linux常见服务器命令
 5.python—WEB服务器运行环境与配置
 6.版本管理工具svn
 7.版本管理工具git
 8.程序部署与网站迁移
 
 
Linux运维动化开发
 1.python开发Linux运维
 2.Linux运维报警工具开发
 3.Linux运维报警安全审计开发
 4.Linux业务质量报表工具开发
 5.Kali安全检测工具检测
 6.Kali密码破解实战
 
 
python数据分析（分析爬虫抓取的数据，分析规律，用于商业化）
 1.numpy数据处理
 2.pandas数据分析
 3.matplotib数据可视化
 4.scipy数据统计分析
 5.python金融数据分析
 
 
python大数据（python操作大数据）
 1.Hadoop HDFS
 2.python Hadoop MapReduce
 3.python Spark core
 4.python Spark SQL
 5.python Spark MLlib
 
 
python机器学习（机器学习的一些入门概念和案例）
 1.机器学习基础知识简介
 2.KNN算法
 3.线性回归
 4.逻辑斯蒂回归算法
 5.决策算法
 6.朴素贝叶斯算法
 7.支持向量机
 8.聚类K-means算法。
 

#pip安装方法    MOOC8.3
#使用pip安装工具
D：、>pip-h
Usage:
   pip<command>[options]
Commands:
   install           Install package.
   download          Download packages.
   uninstall         Uninstall packges.
   freeze            Output installed packages in requirements format.
   list              List installed packages.
   show              Show information about installed package.
   check             Verify installed packages have complatible dependencies.
   search            Search PyPI for packages.
   wheel             Build wheels from yourrequriements.
   help              Show help for commands.
   
#requests库的基本使用框架
import requests 
def getHTMLText(url):
    try:
    r = requests.get(url,timeout=20)
    r.rise_for_status()
    r.endcoding = r.apparent_encoding
    return r.text
    except:
    if_name_=='_main_':
    url = ''


#Scrapy的基本方法的属性
爬虫名称：name属性
启动方法:start_requests()  #创建时原生没有
默认解析器方法：parse（）
启动链接列表：start_url属性


