# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-02 13:50:16（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7868	7.8439	0.8782	0.7525	162.3670
CNY	0.1473		1.1558	0.1294	0.1109	23.9239
HKD	0.1275	0.8652		0.1120	0.0959	20.6998
EUR	1.1387	7.7281	8.9318		0.8569	184.8861
GBP	1.3289	9.0190	10.4238	1.1670		215.7701
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