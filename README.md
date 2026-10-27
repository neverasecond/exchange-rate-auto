# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-27 15:04:48（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6567	7.8430	0.8962	0.7506	157.8540
CNY	0.1502		1.1782	0.1346	0.1128	23.7136
HKD	0.1275	0.8487		0.1143	0.0957	20.1267
EUR	1.1158	7.4277	8.7514		0.8375	176.1370
GBP	1.3323	8.8685	10.4490	1.1940		210.3038
JPY	0.0063	0.0422	0.0497	0.0057	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*