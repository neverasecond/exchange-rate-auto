# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-09 16:11:55（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6827	7.8476	0.8905	0.7552	158.3360
CNY	0.1496		1.1743	0.1333	0.1130	23.6934
HKD	0.1274	0.8516		0.1135	0.0962	20.1764
EUR	1.1230	7.5044	8.8126		0.8481	177.8057
GBP	1.3242	8.8489	10.3914	1.1792		209.6610
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