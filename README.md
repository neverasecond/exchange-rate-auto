# 汇率数据自动更新（美元基准）

**更新时间**：2026-09-11 14:50:41（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7081	7.8415	0.8611	0.7393	154.1880
CNY	0.1491		1.1690	0.1284	0.1102	22.9853
HKD	0.1275	0.8555		0.1098	0.0943	19.6631
EUR	1.1613	7.7902	9.1064		0.8586	179.0593
GBP	1.3526	9.0736	10.6067	1.1648		208.5594
JPY	0.0065	0.0435	0.0509	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*