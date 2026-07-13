# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-13 13:28:41（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7842	7.8383	0.8768	0.7474	162.0480
CNY	0.1474		1.1554	0.1292	0.1102	23.8861
HKD	0.1276	0.8655		0.1119	0.0954	20.6739
EUR	1.1405	7.7375	8.9397		0.8524	184.8175
GBP	1.3380	9.0771	10.4874	1.1731		216.8156
JPY	0.0062	0.0419	0.0484	0.0054	0.0046	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*