# 汇率数据自动更新（美元基准）

**更新时间**：2026-09-18 01:51:51（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6951	7.8458	0.8712	0.7492	155.9970
CNY	0.1494		1.1719	0.1301	0.1119	23.3002
HKD	0.1275	0.8533		0.1110	0.0955	19.8829
EUR	1.1478	7.6849	9.0057		0.8600	179.0599
GBP	1.3348	8.9363	10.4722	1.1628		208.2181
JPY	0.0064	0.0429	0.0503	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*