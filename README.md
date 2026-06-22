# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-22 15:12:13（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7760	7.8385	0.8724	0.7568	161.6950
CNY	0.1476		1.1568	0.1287	0.1117	23.8629
HKD	0.1276	0.8645		0.1113	0.0965	20.6283
EUR	1.1463	7.7671	8.9850		0.8675	185.3450
GBP	1.3214	8.9535	10.3574	1.1527		213.6562
JPY	0.0062	0.0419	0.0485	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*