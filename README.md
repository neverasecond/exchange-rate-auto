# 汇率数据自动更新（美元基准）

**更新时间**：2026-05-22 00:34:48（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.8020	7.8343	0.8623	0.7460	159.1630
CNY	0.1470		1.1518	0.1268	0.1097	23.3994
HKD	0.1276	0.8682		0.1101	0.0952	20.3162
EUR	1.1597	7.8882	9.0854		0.8651	184.5796
GBP	1.3405	9.1180	10.5017	1.1559		213.3552
JPY	0.0063	0.0427	0.0492	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*