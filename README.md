# 汇率数据自动更新（美元基准）

**更新时间**：2026-05-27 01:21:30（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7855	7.8358	0.8599	0.7437	159.2990
CNY	0.1474		1.1548	0.1267	0.1096	23.4764
HKD	0.1276	0.8660		0.1097	0.0949	20.3296
EUR	1.1629	7.8910	9.1125		0.8649	185.2529
GBP	1.3446	9.1240	10.5362	1.1562		214.1979
JPY	0.0063	0.0426	0.0492	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*