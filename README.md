# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-02 03:09:39（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6987	7.8446	0.8897	0.7579	158.0660
CNY	0.1493		1.1711	0.1328	0.1131	23.5965
HKD	0.1275	0.8539		0.1134	0.0966	20.1497
EUR	1.1240	7.5292	8.8171		0.8519	177.6621
GBP	1.3194	8.8385	10.3504	1.1739		208.5579
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