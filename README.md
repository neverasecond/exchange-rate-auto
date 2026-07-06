# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-07 00:47:27（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7812	7.8421	0.8748	0.7478	162.2880
CNY	0.1475		1.1564	0.1290	0.1103	23.9320
HKD	0.1275	0.8647		0.1116	0.0954	20.6945
EUR	1.1431	7.7517	8.9644		0.8548	185.5144
GBP	1.3373	9.0682	10.4869	1.1698		217.0206
JPY	0.0062	0.0418	0.0483	0.0054	0.0046	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*