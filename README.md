# 汇率数据自动更新（美元基准）

**更新时间**：2026-05-05 12:54:40（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.8271	7.8353	0.8556	0.7394	157.2640
CNY	0.1465		1.1477	0.1253	0.1083	23.0353
HKD	0.1276	0.8713		0.1092	0.0944	20.0712
EUR	1.1688	7.9793	9.1577		0.8642	183.8055
GBP	1.3524	9.2333	10.5968	1.1572		212.6914
JPY	0.0064	0.0434	0.0498	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*