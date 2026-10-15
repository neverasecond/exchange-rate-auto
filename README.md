# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-16 01:55:56（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6804	7.8473	0.8913	0.7534	158.1180
CNY	0.1497		1.1747	0.1334	0.1128	23.6689
HKD	0.1274	0.8513		0.1136	0.0960	20.1494
EUR	1.1220	7.4951	8.8043		0.8453	177.4015
GBP	1.3273	8.8670	10.4158	1.1830		209.8726
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