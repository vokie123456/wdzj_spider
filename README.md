# wdzj_spider
R语言网贷之家数据爬虫

----------------------------------------------------------------------------------------------------------------------------------------
# 爬虫目标

抓取网贷之家平台数据，爬虫网站：http://shuju.wdzj.com/

![爬虫网站](https://github.com/laidefa/wdzj_spider/raw/master/resource/web.png)



# 自定义

可设置时间按天、按月抓取。

### 定义抓取日期(按天)

shujuDate <- "2018-01-232018-01-23"


### 定义抓取日期(按月）

shujuDate <- "2017-12-012017-12-31"


----------------------------------------------------------------------------------------------------------------------------------------
# 抓取效果
共16个字段

- 平台名称
- 成交量
- 平均参考收益率
- 平均借款期限
- 资金净流入
- 待还余额
- 满标用时
- 注册资本
- 运营时间
- 借款标数
- 投资人数
- 人均投资金额
- 前十大土豪待收金额占比
- 借款人数
- 人均借款金额
- 前十大借款人待还金额占比



![数据](https://github.com/laidefa/wdzj_spider/raw/master/resource/result.png)

----------------------------------------------------------------------------------------------------------------------------------------
# 安装包

install.packages("XML")

install.packages("RCurl")

install.packages("RJSONIO")

----------------------------------------------------------------------------------------------------------------------------------------
# 导入包

library(XML)

library(RCurl)

library(RJSONIO)

----------------------------------------------------------------------------------------------------------------------------------------
# 主要技术
1、R语言如何发送post请求

2、R语言如何解析json,fromJSON函数的使用（来自RJSONIO包）

3、R语言数据处理，合并数据框，重命名。

4、R语言写出excel。

---------------------------------------------------------------------------------------------------------------------------------------



