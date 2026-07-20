# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-20 23:44:48（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7564	7.8401	0.8764	0.7454	162.5670
CNY	0.1480		1.1604	0.1297	0.1103	24.0612
HKD	0.1275	0.8618		0.1118	0.0951	20.7353
EUR	1.1410	7.7093	8.9458		0.8505	185.4941
GBP	1.3416	9.0641	10.5180	1.1757		218.0936
JPY	0.0062	0.0416	0.0482	0.0054	0.0046	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*