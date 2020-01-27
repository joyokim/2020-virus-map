Intro
========

Base on China official news to pop up virus cases on map. 

基于中国官方新闻公布数据，绘制新型冠状病毒案例于地图上。

**目前数据非实时更新。欢迎提交 pull request。目前在编写数据爬虫中，数据来源为各地方卫生委员会网站 2020-01-22 10:43**

**All rendering data are not realtime updates. Robot is in development. Will be pleased if you could join us for making contribution.**

**2020-01-22 给在写爬虫的朋友两个信息**

> 在本项目中，已经上传了全国所有城市的名称以及对应的经纬度坐标。存储在 `city_position.json` 文件中。

> 在本项目中，已经上传了全国个地方卫生委员会网站的地址 存储在 `cities_health_commission_department_website.txt` 文件中。 

更新于：2020-01-22 17:46 

How to contribute 
=============

### Update case number or city 

1. `Fork` this repository
2. `Edit` virus-data.json file 
3. `Add` or `update` city, number, news source 
4. `Merge` new a pull request  

### Update UI or other program 

Please check out the following repo to make map app better : [2020-virus-app](https://github.com/lbj96347/2020-new-coronavirus-live-map)

Please check out the following repo to make crawler script better : [2020-new-coronavirus-info-crawler](https://github.com/lbj96347/2020-new-coronavirus-info-crawler)

您可以到这里对 UI 改进: [2020-virus-app](https://github.com/lbj96347/2020-new-coronavirus-live-map)

您可以到这里对爬虫改进: [2020-new-coronavirus-info-crawler](https://github.com/lbj96347/2020-new-coronavirus-info-crawler)

### Notice 

All news sources should be published by Chinese goverment departments 

请提交 merge request 的时候注意检查您的新闻源来自中国政府的官方机构

To be continue
==============

📝 Update UI/UX in this webview 

🕸 Add auto Web crawlers to grab latest news & update sources
