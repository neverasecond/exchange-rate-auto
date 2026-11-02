# 汇率数据自动更新（美元基准）

**更新时间**：2026-11-03 06:31:01（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6374	7.8459	0.8933	0.7459	157.8640
CNY	0.1507		1.1821	0.1346	0.1124	23.7840
HKD	0.1275	0.8460		0.1139	0.0951	20.1206
EUR	1.1194	7.4302	8.7831		0.8350	176.7200
GBP	1.3407	8.8985	10.5187	1.1976		211.6423
JPY	0.0063	0.0420	0.0497	0.0057	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*