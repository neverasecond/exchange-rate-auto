# 汇率数据自动更新（美元基准）

**更新时间**：2026-09-30 15:44:03（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7042	7.8453	0.8811	0.7538	156.8680
CNY	0.1492		1.1702	0.1314	0.1124	23.3985
HKD	0.1275	0.8545		0.1123	0.0961	19.9952
EUR	1.1349	7.6089	8.9040		0.8555	178.0365
GBP	1.3266	8.8939	10.4077	1.1689		208.1029
JPY	0.0064	0.0427	0.0500	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*