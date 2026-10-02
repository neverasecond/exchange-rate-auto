# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-03 02:49:35（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7045	7.8466	0.8885	0.7554	157.7800
CNY	0.1492		1.1703	0.1325	0.1127	23.5334
HKD	0.1274	0.8544		0.1132	0.0963	20.1081
EUR	1.1255	7.5459	8.8313		0.8502	177.5802
GBP	1.3238	8.8754	10.3873	1.1762		208.8695
JPY	0.0063	0.0425	0.0497	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*