# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-23 13:59:23（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7801	7.8387	0.8753	0.7552	161.6630
CNY	0.1475		1.1561	0.1291	0.1114	23.8437
HKD	0.1276	0.8650		0.1117	0.0963	20.6237
EUR	1.1425	7.7460	8.9554		0.8628	184.6944
GBP	1.3242	8.9779	10.3796	1.1590		214.0665
JPY	0.0062	0.0419	0.0485	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*