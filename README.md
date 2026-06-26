# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-27 00:07:23（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7869	7.8416	0.8768	0.7565	161.6600
CNY	0.1473		1.1554	0.1292	0.1115	23.8194
HKD	0.1275	0.8655		0.1118	0.0965	20.6157
EUR	1.1405	7.7405	8.9434		0.8628	184.3750
GBP	1.3219	8.9714	10.3656	1.1590		213.6946
JPY	0.0062	0.0420	0.0485	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*