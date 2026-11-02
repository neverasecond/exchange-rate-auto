# 汇率数据自动更新（美元基准）

**更新时间**：2026-11-02 16:38:59（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6442	7.8462	0.8916	0.7447	157.6290
CNY	0.1505		1.1809	0.1342	0.1121	23.7243
HKD	0.1275	0.8468		0.1136	0.0949	20.0899
EUR	1.1216	7.4520	8.8001		0.8352	176.7934
GBP	1.3428	8.9220	10.5361	1.1973		211.6678
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