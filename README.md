# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-15 14:45:05（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6915	7.8474	0.8922	0.7554	157.9840
CNY	0.1494		1.1727	0.1333	0.1129	23.6097
HKD	0.1274	0.8527		0.1137	0.0963	20.1320
EUR	1.1208	7.5000	8.7956		0.8467	177.0724
GBP	1.3238	8.8582	10.3884	1.1811		209.1395
JPY	0.0063	0.0424	0.0497	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*