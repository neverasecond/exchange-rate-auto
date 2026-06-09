# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-10 00:25:48（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7717	7.8372	0.8660	0.7477	160.3210
CNY	0.1477		1.1573	0.1279	0.1104	23.6751
HKD	0.1276	0.8640		0.1105	0.0954	20.4564
EUR	1.1547	7.8195	9.0499		0.8634	185.1282
GBP	1.3374	9.0567	10.4817	1.1582		214.4189
JPY	0.0062	0.0422	0.0489	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*