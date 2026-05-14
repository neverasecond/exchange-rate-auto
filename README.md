# 汇率数据自动更新（美元基准）

**更新时间**：2026-05-15 00:05:12（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7846	7.8323	0.8562	0.7420	158.0960
CNY	0.1474		1.1544	0.1262	0.1094	23.3022
HKD	0.1277	0.8662		0.1093	0.0947	20.1851
EUR	1.1680	7.9241	9.1477		0.8666	184.6484
GBP	1.3477	9.1437	10.5557	1.1539		213.0674
JPY	0.0063	0.0429	0.0495	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*