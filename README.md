# 2019nCov-API
2019nCov-API

# Data Sources
- history data: https://github.com/BlankerL/DXY-2019-nCoV-Data
- real-time data: https://ncov.dxy.cn/ncovh5/view/pneumonia
- historical travel data: http://2019ncov.nosugartech.com
- map api: http://api.map.baidu.com/ 

# Data Structures
- h_travel_stats

| id | t_date | t_type | o_type | t_start | t_stop |
|----|--------|--------|--------|---------|--------|
|    |        |        |        |         |        |
|    |        |        |        |         |        |
|    |        |        |        |         |        |



- geo_points
| id | country | province | city | geometrics |
|----|---------|----------|------|------------|
|    |         |          |      |            |
|    |         |          |      |            |
|    |         |          |      |            |

- stats

| id | country | provinceName | cityName | province_confirmedCount | province_suspectedCount | province_curedCount | province_deadCount | city_confirmedCount | city_suspectedCount | city_curedCount | city_deadCount | updateTime              |
|----|---------|--------------|----------|-------------------------|-------------------------|---------------------|--------------------|---------------------|---------------------|-----------------|----------------|-------------------------|
| 0  | 中国    | 山东省       | 青岛     | 259                     | 0                       | 7                   | 0                  | 26                  | 0                   | 1               | 0              | 2020-02-03 22:33:28.253 |
| 1  | 中国    | 山东省       | 烟台     | 259                     | 0                       | 7                   | 0                  | 26                  | 0                   | 0               | 0              | 2020-02-03 22:33:28.253 |