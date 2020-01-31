# 2019nCov-API
2019nCov-API

# Data Sources
- history data: https://github.com/BlankerL/DXY-2019-nCoV-Data
- real-time data: https://ncov.dxy.cn/ncovh5/view/pneumonia
- historical travel data: http://2019ncov.nosugartech.com
- map api: http://api.map.baidu.com/ 

# Data Structures
- h_travel_stats

| id | t_date     | t_type | t_start | t_stop | path_POLYGON   |
|----|------------|--------|---------|--------|----------------|
| 1  | 2010-01-08 | 1      | 哈尔滨  | 海口   | [（lat,lng）, (lat, lng)] |
|    |            |        |         |        |                |
|    |            |        |         |        |                |


- geo_points

| id | country | province | city | geo_point    |   |
|----|---------|----------|------|--------------|---|
| 1  | 中国    | 湖北     | 武汉 | （lat，lng） |   |
|    |         |          |      |              |   |
|    |         |          |      |              |   |
|    |         |          |      |              |   |

- stats

| id | t_date | country | province | city | confirmed | suspected | cured | dead |
|----|--------|---------|----------|------|-----------|-----------|-------|------|
|    |        |         |          |      |           |           |       |      |
|    |        |         |          |      |           |           |       |      |
|    |        |         |          |      |           |           |       |      |
|    |        |         |          |      |           |           |       |      |