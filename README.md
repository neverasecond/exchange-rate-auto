# 汇率数据自动更新（美元基准）

**更新时间**：2026-11-12 04:59:32（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6631	7.8448	0.9015	0.7533	159.8520
CNY	0.1501		1.1773	0.1353	0.1131	23.9906
HKD	0.1275	0.8494		0.1149	0.0960	20.3768
EUR	1.1093	7.3911	8.7019		0.8356	177.3178
GBP	1.3275	8.8452	10.4139	1.1967		212.2023
JPY	0.0063	0.0417	0.0491	0.0056	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*