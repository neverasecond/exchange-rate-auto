# 汇率数据自动更新（美元基准）

**更新时间**：2026-11-14 04:42:03（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6705	7.8457	0.9070	0.7570	159.7950
CNY	0.1499		1.1762	0.1360	0.1135	23.9555
HKD	0.1275	0.8502		0.1156	0.0965	20.3672
EUR	1.1025	7.3545	8.6502		0.8346	176.1797
GBP	1.3210	8.8118	10.3642	1.1982		211.0898
JPY	0.0063	0.0417	0.0491	0.0057	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*