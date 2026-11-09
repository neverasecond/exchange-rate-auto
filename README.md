# 汇率数据自动更新（美元基准）

**更新时间**：2026-11-09 16:52:57（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6621	7.8419	0.8938	0.7457	158.1270
CNY	0.1501		1.1771	0.1342	0.1119	23.7353
HKD	0.1275	0.8496		0.1140	0.0951	20.1644
EUR	1.1188	7.4537	8.7737		0.8343	176.9154
GBP	1.3410	8.9340	10.5162	1.1986		212.0518
JPY	0.0063	0.0421	0.0496	0.0057	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*