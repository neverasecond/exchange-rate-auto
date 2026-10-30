# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-30 15:54:15（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6447	7.8456	0.8938	0.7462	157.5820
CNY	0.1505		1.1807	0.1345	0.1123	23.7154
HKD	0.1275	0.8469		0.1139	0.0951	20.0854
EUR	1.1188	7.4342	8.7778		0.8349	176.3057
GBP	1.3401	8.9047	10.5141	1.1978		211.1793
JPY	0.0063	0.0422	0.0498	0.0057	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*