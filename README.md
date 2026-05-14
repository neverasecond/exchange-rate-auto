# 汇率数据自动更新（美元基准）

**更新时间**：2026-05-14 13:40:46（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7855	7.8314	0.8535	0.7398	157.8850
CNY	0.1474		1.1541	0.1258	0.1090	23.2680
HKD	0.1277	0.8664		0.1090	0.0945	20.1605
EUR	1.1716	7.9502	9.1756		0.8668	184.9854
GBP	1.3517	9.1721	10.5858	1.1537		213.4158
JPY	0.0063	0.0430	0.0496	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*