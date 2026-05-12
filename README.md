# 汇率数据自动更新（美元基准）

**更新时间**：2026-05-12 13:31:55（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7927	7.8282	0.8504	0.7366	157.6920
CNY	0.1472		1.1524	0.1252	0.1084	23.2149
HKD	0.1277	0.8677		0.1086	0.0941	20.1441
EUR	1.1759	7.9877	9.2053		0.8662	185.4327
GBP	1.3576	9.2217	10.6275	1.1545		214.0809
JPY	0.0063	0.0431	0.0496	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*