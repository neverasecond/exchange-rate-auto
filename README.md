# 汇率数据自动更新（美元基准）

**更新时间**：2026-09-25 14:52:36（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7037	7.8429	0.8782	0.7561	158.0310
CNY	0.1492		1.1699	0.1310	0.1128	23.5737
HKD	0.1275	0.8547		0.1120	0.0964	20.1496
EUR	1.1387	7.6335	8.9307		0.8610	179.9488
GBP	1.3226	8.8662	10.3728	1.1615		209.0081
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