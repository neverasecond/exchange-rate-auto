# 汇率数据自动更新（美元基准）

**更新时间**：2026-05-20 13:58:50（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.8107	7.8320	0.8622	0.7467	158.9790
CNY	0.1468		1.1500	0.1266	0.1096	23.3425
HKD	0.1277	0.8696		0.1101	0.0953	20.2986
EUR	1.1598	7.8992	9.0837		0.8660	184.3876
GBP	1.3392	9.1211	10.4888	1.1547		212.9088
JPY	0.0063	0.0428	0.0493	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*