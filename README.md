# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-01 14:46:20（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7657	7.8365	0.8578	0.7425	159.4730
CNY	0.1478		1.1583	0.1268	0.1097	23.5708
HKD	0.1276	0.8634		0.1095	0.0947	20.3500
EUR	1.1658	7.8873	9.1356		0.8656	185.9093
GBP	1.3468	9.1121	10.5542	1.1553		214.7785
JPY	0.0063	0.0424	0.0491	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*