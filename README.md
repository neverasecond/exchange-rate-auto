# 汇率数据自动更新（美元基准）

**更新时间**：2026-09-15 14:59:05（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7125	7.8432	0.8669	0.7425	154.9390
CNY	0.1490		1.1684	0.1291	0.1106	23.0822
HKD	0.1275	0.8558		0.1105	0.0947	19.7546
EUR	1.1535	7.7431	9.0474		0.8565	178.7277
GBP	1.3468	9.0404	10.5632	1.1675		208.6721
JPY	0.0065	0.0433	0.0506	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*