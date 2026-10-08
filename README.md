# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-08 16:11:35（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7017	7.8469	0.8932	0.7574	158.1930
CNY	0.1492		1.1709	0.1333	0.1130	23.6049
HKD	0.1274	0.8541		0.1138	0.0965	20.1599
EUR	1.1196	7.5030	8.7852		0.8480	177.1082
GBP	1.3203	8.8483	10.3603	1.1793		208.8632
JPY	0.0063	0.0424	0.0496	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*