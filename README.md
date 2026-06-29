# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-30 00:49:18（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7854	7.8427	0.8749	0.7544	161.9280
CNY	0.1474		1.1558	0.1289	0.1112	23.8642
HKD	0.1275	0.8652		0.1116	0.0962	20.6470
EUR	1.1430	7.7556	8.9641		0.8623	185.0817
GBP	1.3256	8.9944	10.3959	1.1597		214.6448
JPY	0.0062	0.0419	0.0484	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*