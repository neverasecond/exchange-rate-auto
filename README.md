# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-28 03:06:03（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6558	7.8446	0.8978	0.7510	157.9120
CNY	0.1502		1.1786	0.1349	0.1128	23.7255
HKD	0.1275	0.8485		0.1144	0.0957	20.1300
EUR	1.1138	7.4135	8.7376		0.8365	175.8877
GBP	1.3316	8.8626	10.4455	1.1955		210.2690
JPY	0.0063	0.0421	0.0497	0.0057	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*