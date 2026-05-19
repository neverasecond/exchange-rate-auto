# 汇率数据自动更新（美元基准）

**更新时间**：2026-05-20 00:45:36（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.8139	7.8327	0.8612	0.7462	158.7970
CNY	0.1468		1.1495	0.1264	0.1095	23.3049
HKD	0.1277	0.8699		0.1099	0.0953	20.2736
EUR	1.1612	7.9121	9.0951		0.8665	184.3904
GBP	1.3401	9.1315	10.4968	1.1541		212.8076
JPY	0.0063	0.0429	0.0493	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*