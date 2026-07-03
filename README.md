# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-03 13:44:30（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7793	7.8420	0.8730	0.7479	161.1270
CNY	0.1475		1.1568	0.1288	0.1103	23.7675
HKD	0.1275	0.8645		0.1113	0.0954	20.5467
EUR	1.1455	7.7655	8.9828		0.8567	184.5670
GBP	1.3371	9.0644	10.4854	1.1673		215.4392
JPY	0.0062	0.0421	0.0487	0.0054	0.0046	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*