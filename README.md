# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-14 03:59:23（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6817	7.8480	0.8928	0.7545	158.3380
CNY	0.1497		1.1746	0.1336	0.1129	23.6973
HKD	0.1274	0.8514		0.1138	0.0961	20.1756
EUR	1.1201	7.4840	8.7903		0.8451	177.3499
GBP	1.3254	8.8558	10.4016	1.1833		209.8582
JPY	0.0063	0.0422	0.0496	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*