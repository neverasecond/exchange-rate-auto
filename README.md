# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-19 00:50:48（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7705	7.8376	0.8719	0.7563	161.3320
CNY	0.1477		1.1576	0.1288	0.1117	23.8287
HKD	0.1276	0.8638		0.1112	0.0965	20.5844
EUR	1.1469	7.7652	8.9891		0.8674	185.0350
GBP	1.3222	8.9521	10.3631	1.1528		213.3175
JPY	0.0062	0.0420	0.0486	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*