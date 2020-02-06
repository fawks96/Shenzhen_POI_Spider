# Shenzhen_POI_Spider
A spider for Shenzhen POI

## 概述
基于百度地图开放平台来实现POI的爬取任务，爬取的信息中，包括如下字段：['name', 'province', 'city', 'area', 'address', 'telephone', 'uid', 'street_id', 'detail', 'detail_info', 'location']

&ensp;

- **run.py**

  程序运行入口
  
 - **BaiduMapWebApiSpier/settings.py**

    进行程序配置设置（API Key、mysql数据库配置、通知邮件设置）
  
- **BaiduMapWebApiSpier/spiders/web_api_spider.py**

  主功能代码。通过请求百度地图API获取相关POI信息。
  
 - **BaiduMapWebApiSpier/pipelines.py**

    将获取数据存入Mysql数据区




