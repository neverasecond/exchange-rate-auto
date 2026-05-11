# 汇率数据自动更新（美元基准）

**更新时间**：2026-05-11 13:51:41（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7957	7.8296	0.8509	0.7362	157.1380
CNY	0.1472		1.1521	0.1252	0.1083	23.1232
HKD	0.1277	0.8679		0.1087	0.0940	20.0697
EUR	1.1752	7.9865	9.2016		0.8652	184.6727
GBP	1.3583	9.2308	10.6352	1.1558		213.4447
JPY	0.0064	0.0432	0.0498	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*