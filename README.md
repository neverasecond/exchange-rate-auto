# 汇率数据自动更新（美元基准）

**更新时间**：2026-09-10 14:50:42（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7062	7.8408	0.8589	0.7376	153.5450
CNY	0.1491		1.1692	0.1281	0.1100	22.8960
HKD	0.1275	0.8553		0.1095	0.0941	19.5828
EUR	1.1643	7.8079	9.1289		0.8588	178.7694
GBP	1.3557	9.0919	10.6302	1.1645		208.1684
JPY	0.0065	0.0437	0.0511	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*