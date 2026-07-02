# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-02 23:59:47（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7735	7.8423	0.8733	0.7484	160.9190
CNY	0.1476		1.1578	0.1289	0.1105	23.7571
HKD	0.1275	0.8637		0.1114	0.0954	20.5194
EUR	1.1451	7.7562	8.9801		0.8570	184.2654
GBP	1.3362	9.0506	10.4788	1.1669		215.0174
JPY	0.0062	0.0421	0.0487	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*