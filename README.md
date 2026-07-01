# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-01 14:17:26（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7927	7.8430	0.8766	0.7551	162.7100
CNY	0.1472		1.1546	0.1291	0.1112	23.9537
HKD	0.1275	0.8661		0.1118	0.0963	20.7459
EUR	1.1408	7.7489	8.9471		0.8614	185.6149
GBP	1.3243	8.9958	10.3867	1.1609		215.4814
JPY	0.0061	0.0417	0.0482	0.0054	0.0046	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*