# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-19 14:57:08（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7675	7.8384	0.8740	0.7579	161.2720
CNY	0.1478		1.1582	0.1291	0.1120	23.8304
HKD	0.1276	0.8634		0.1115	0.0967	20.5746
EUR	1.1442	7.7431	8.9684		0.8672	184.5217
GBP	1.3194	8.9293	10.3423	1.1532		212.7880
JPY	0.0062	0.0420	0.0486	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*