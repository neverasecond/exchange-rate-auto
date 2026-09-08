# 汇率数据自动更新（美元基准）

**更新时间**：2026-09-09 01:40:17（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6982	7.8413	0.8600	0.7387	154.2780
CNY	0.1493		1.1707	0.1284	0.1103	23.0328
HKD	0.1275	0.8542		0.1097	0.0942	19.6751
EUR	1.1628	7.7886	9.1178		0.8590	179.3930
GBP	1.3537	9.0676	10.6150	1.1642		208.8507
JPY	0.0065	0.0434	0.0508	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*