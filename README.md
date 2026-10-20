# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-20 14:53:24（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6782	7.8479	0.8902	0.7489	158.1510
CNY	0.1497		1.1752	0.1333	0.1121	23.6817
HKD	0.1274	0.8510		0.1134	0.0954	20.1520
EUR	1.1233	7.5019	8.8159		0.8413	177.6578
GBP	1.3353	8.9173	10.4792	1.1887		211.1777
JPY	0.0063	0.0422	0.0496	0.0056	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*