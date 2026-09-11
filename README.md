# 汇率数据自动更新（美元基准）

**更新时间**：2026-09-12 01:25:31（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6964	7.8427	0.8618	0.7394	153.6690
CNY	0.1493		1.1712	0.1287	0.1104	22.9480
HKD	0.1275	0.8538		0.1099	0.0943	19.5939
EUR	1.1604	7.7702	9.1004		0.8580	178.3117
GBP	1.3524	9.0565	10.6068	1.1655		207.8293
JPY	0.0065	0.0436	0.0510	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*