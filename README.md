# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-02 03:15:43（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7650	7.8373	0.8595	0.7430	159.6790
CNY	0.1478		1.1585	0.1271	0.1098	23.6037
HKD	0.1276	0.8632		0.1097	0.0948	20.3742
EUR	1.1635	7.8709	9.1184		0.8645	185.7813
GBP	1.3459	9.1050	10.5482	1.1568		214.9112
JPY	0.0063	0.0424	0.0491	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*