# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-12 16:18:51（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6923	7.8474	0.8932	0.7553	158.4480
CNY	0.1494		1.1726	0.1335	0.1129	23.6762
HKD	0.1274	0.8528		0.1138	0.0962	20.1911
EUR	1.1196	7.4925	8.7857		0.8456	177.3936
GBP	1.3240	8.8605	10.3898	1.1826		209.7815
JPY	0.0063	0.0422	0.0495	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*