# 汇率数据自动更新（美元基准）

**更新时间**：2026-11-13 05:14:54（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6699	7.8445	0.9043	0.7555	159.8580
CNY	0.1499		1.1761	0.1356	0.1133	23.9671
HKD	0.1275	0.8503		0.1153	0.0963	20.3784
EUR	1.1058	7.3758	8.6747		0.8355	176.7754
GBP	1.3236	8.8285	10.3832	1.1970		211.5923
JPY	0.0063	0.0417	0.0491	0.0057	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*