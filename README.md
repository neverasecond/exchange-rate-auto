# 汇率数据自动更新（美元基准）

**更新时间**：2026-05-19 13:59:04（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7982	7.8311	0.8588	0.7454	159.0190
CNY	0.1471		1.1519	0.1263	0.1096	23.3913
HKD	0.1277	0.8681		0.1097	0.0952	20.3061
EUR	1.1644	7.9159	9.1187		0.8680	185.1642
GBP	1.3416	9.1202	10.5059	1.1521		213.3338
JPY	0.0063	0.0428	0.0492	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*