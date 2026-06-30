# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-30 14:02:26（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7787	7.8424	0.8781	0.7561	162.3160
CNY	0.1475		1.1569	0.1295	0.1115	23.9450
HKD	0.1275	0.8644		0.1120	0.0964	20.6972
EUR	1.1388	7.7197	8.9311		0.8611	184.8491
GBP	1.3226	8.9653	10.3722	1.1614		214.6753
JPY	0.0062	0.0418	0.0483	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*