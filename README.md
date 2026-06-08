# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-08 14:28:36（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7840	7.8345	0.8676	0.7502	160.3300
CNY	0.1474		1.1548	0.1279	0.1106	23.6335
HKD	0.1276	0.8659		0.1107	0.0958	20.4646
EUR	1.1526	7.8193	9.0301		0.8647	184.7971
GBP	1.3330	9.0429	10.4432	1.1565		213.7163
JPY	0.0062	0.0423	0.0489	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*