# 汇率数据自动更新（美元基准）

**更新时间**：2026-09-17 01:51:56（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6945	7.8444	0.8668	0.7438	155.1170
CNY	0.1494		1.1718	0.1295	0.1111	23.1708
HKD	0.1275	0.8534		0.1105	0.0948	19.7742
EUR	1.1537	7.7232	9.0498		0.8581	178.9536
GBP	1.3444	9.0004	10.5464	1.1654		208.5467
JPY	0.0064	0.0432	0.0506	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*