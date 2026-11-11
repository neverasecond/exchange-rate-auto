# 汇率数据自动更新（美元基准）

**更新时间**：2026-11-11 16:39:23（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6679	7.8459	0.8968	0.7506	158.8660
CNY	0.1500		1.1767	0.1345	0.1126	23.8255
HKD	0.1275	0.8499		0.1143	0.0957	20.2483
EUR	1.1151	7.4352	8.7488		0.8370	177.1476
GBP	1.3323	8.8834	10.4528	1.1948		211.6520
JPY	0.0063	0.0420	0.0494	0.0056	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*