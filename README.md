# 汇率数据自动更新（美元基准）

**更新时间**：2026-05-18 14:04:44（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.8106	7.8281	0.8601	0.7503	158.9300
CNY	0.1468		1.1494	0.1263	0.1102	23.3357
HKD	0.1277	0.8700		0.1099	0.0958	20.3025
EUR	1.1627	7.9184	9.1014		0.8723	184.7808
GBP	1.3328	9.0772	10.4333	1.1463		211.8219
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