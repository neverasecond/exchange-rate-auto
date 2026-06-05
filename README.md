# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-05 14:13:41（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7748	7.8322	0.8608	0.7448	159.9550
CNY	0.1476		1.1561	0.1271	0.1099	23.6103
HKD	0.1277	0.8650		0.1099	0.0951	20.4227
EUR	1.1617	7.8704	9.0987		0.8652	185.8213
GBP	1.3426	9.0961	10.5158	1.1557		214.7624
JPY	0.0063	0.0424	0.0490	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*