# infectedparse
python爬取全国感染新冠人数，并绘制疫情地图

一、主要功能
python将全国各地感染新型肺炎信息爬取下来，存储在mysql数据库，并用flask框架将数据展示在web上，并绘制出疫情地图
展示数据时，选择疫情发生地点，下拉框选择时有省-市二级联动。

infectedparse\InfectionStat\src里面有sql文件，confirmedstat.sql是爬取后导出的各个地区感染人数sql，pushservice.sql是爬取的消息推送sql,createTable.sql是建表sql，

二、涉及技术
flask,layui,mysql5.6,pymysql


