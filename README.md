# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-17 02:23:56（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7557	7.8330	0.8610	0.7447	160.4280
CNY	0.1480		1.1595	0.1274	0.1102	23.7471
HKD	0.1277	0.8625		0.1099	0.0951	20.4810
EUR	1.1614	7.8463	9.0976		0.8649	186.3275
GBP	1.3428	9.0717	10.5183	1.1562		215.4263
JPY	0.0062	0.0421	0.0488	0.0054	0.0046	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*