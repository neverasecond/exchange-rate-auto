# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-07 15:57:18（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6933	7.8472	0.8939	0.7557	158.0690
CNY	0.1494		1.1724	0.1336	0.1129	23.6160
HKD	0.1274	0.8530		0.1139	0.0963	20.1434
EUR	1.1187	7.4878	8.7786		0.8454	176.8307
GBP	1.3233	8.8571	10.3840	1.1829		209.1690
JPY	0.0063	0.0423	0.0496	0.0057	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*