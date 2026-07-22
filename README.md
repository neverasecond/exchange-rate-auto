# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-22 23:25:43（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7608	7.8398	0.8760	0.7476	163.1030
CNY	0.1479		1.1596	0.1296	0.1106	24.1248
HKD	0.1276	0.8624		0.1117	0.0954	20.8045
EUR	1.1416	7.7178	8.9495		0.8534	186.1906
GBP	1.3376	9.0433	10.4866	1.1717		218.1688
JPY	0.0061	0.0415	0.0481	0.0054	0.0046	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*