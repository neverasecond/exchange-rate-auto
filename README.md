# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-16 02:20:15（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7565	7.8344	0.8618	0.7447	160.2740
CNY	0.1480		1.1595	0.1276	0.1102	23.7215
HKD	0.1276	0.8624		0.1100	0.0951	20.4577
EUR	1.1604	7.8400	9.0907		0.8641	185.9759
GBP	1.3428	9.0728	10.5202	1.1572		215.2196
JPY	0.0062	0.0422	0.0489	0.0054	0.0046	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*