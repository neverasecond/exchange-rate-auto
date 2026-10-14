# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-14 14:54:40（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6915	7.8478	0.8918	0.7536	158.2560
CNY	0.1494		1.1728	0.1333	0.1126	23.6503
HKD	0.1274	0.8527		0.1136	0.0960	20.1657
EUR	1.1213	7.5034	8.8000		0.8450	177.4568
GBP	1.3270	8.8794	10.4137	1.1834		210.0000
JPY	0.0063	0.0423	0.0496	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*