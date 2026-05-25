# 汇率数据自动更新（美元基准）

**更新时间**：2026-05-25 14:18:08（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7804	7.8350	0.8590	0.7418	158.9000
CNY	0.1475		1.1555	0.1267	0.1094	23.4352
HKD	0.1276	0.8654		0.1096	0.0947	20.2808
EUR	1.1641	7.8934	9.1211		0.8636	184.9825
GBP	1.3481	9.1405	10.5621	1.1580		214.2087
JPY	0.0063	0.0427	0.0493	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*