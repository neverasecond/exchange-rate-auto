# 汇率数据自动更新（美元基准）

**更新时间**：2026-09-19 01:22:33（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6873	7.8454	0.8706	0.7467	156.6770
CNY	0.1495		1.1732	0.1302	0.1117	23.4290
HKD	0.1275	0.8524		0.1110	0.0952	19.9706
EUR	1.1486	7.6813	9.0115		0.8577	179.9644
GBP	1.3392	8.9558	10.5068	1.1659		209.8259
JPY	0.0064	0.0427	0.0501	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*