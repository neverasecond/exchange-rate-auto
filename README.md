# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-17 23:06:12（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7660	7.8401	0.8737	0.7435	162.3910
CNY	0.1478		1.1587	0.1291	0.1099	24.0010
HKD	0.1275	0.8630		0.1114	0.0948	20.7129
EUR	1.1446	7.7441	8.9734		0.8510	185.8659
GBP	1.3450	9.1002	10.5449	1.1751		218.4143
JPY	0.0062	0.0417	0.0483	0.0054	0.0046	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*