# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-21 13:12:22（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7653	7.8411	0.8756	0.7440	162.5080
CNY	0.1478		1.1590	0.1294	0.1100	24.0208
HKD	0.1275	0.8628		0.1117	0.0949	20.7252
EUR	1.1421	7.7265	8.9551		0.8497	185.5962
GBP	1.3441	9.0931	10.5391	1.1769		218.4247
JPY	0.0062	0.0416	0.0483	0.0054	0.0046	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*