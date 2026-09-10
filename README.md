# 汇率数据自动更新（美元基准）

**更新时间**：2026-09-11 01:24:01（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7010	7.8414	0.8601	0.7391	154.2140
CNY	0.1492		1.1702	0.1284	0.1103	23.0136
HKD	0.1275	0.8546		0.1097	0.0943	19.6666
EUR	1.1627	7.7910	9.1168		0.8593	179.2978
GBP	1.3530	9.0664	10.6094	1.1637		208.6511
JPY	0.0065	0.0435	0.0508	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*