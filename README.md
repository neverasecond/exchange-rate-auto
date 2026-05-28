# 汇率数据自动更新（美元基准）

**更新时间**：2026-05-28 14:03:01（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7819	7.8309	0.8618	0.7466	159.5460
CNY	0.1475		1.1547	0.1271	0.1101	23.5253
HKD	0.1277	0.8660		0.1101	0.0953	20.3739
EUR	1.1604	7.8695	9.0867		0.8663	185.1311
GBP	1.3394	9.0837	10.4887	1.1543		213.6968
JPY	0.0063	0.0425	0.0491	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*