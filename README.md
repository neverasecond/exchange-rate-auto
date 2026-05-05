# 汇率数据自动更新（美元基准）

**更新时间**：2026-05-05 23:29:49（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.8295	7.8361	0.8541	0.7372	157.7130
CNY	0.1464		1.1474	0.1251	0.1079	23.0929
HKD	0.1276	0.8715		0.1090	0.0941	20.1265
EUR	1.1708	7.9961	9.1747		0.8631	184.6540
GBP	1.3565	9.2641	10.6295	1.1586		213.9352
JPY	0.0063	0.0433	0.0497	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*