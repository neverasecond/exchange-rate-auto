# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-06 16:20:22（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6918	7.8475	0.8904	0.7559	158.2110
CNY	0.1494		1.1727	0.1331	0.1130	23.6425
HKD	0.1274	0.8527		0.1135	0.0963	20.1607
EUR	1.1231	7.5155	8.8135		0.8489	177.6853
GBP	1.3229	8.8528	10.3817	1.1779		209.3015
JPY	0.0063	0.0423	0.0496	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*