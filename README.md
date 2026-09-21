# 汇率数据自动更新（美元基准）

**更新时间**：2026-09-21 15:26:18（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6951	7.8452	0.8712	0.7475	157.2140
CNY	0.1494		1.1718	0.1301	0.1116	23.4819
HKD	0.1275	0.8534		0.1110	0.0953	20.0395
EUR	1.1478	7.6849	9.0051		0.8580	180.4568
GBP	1.3378	8.9567	10.4953	1.1655		210.3197
JPY	0.0064	0.0426	0.0499	0.0055	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*