# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-01 00:16:45（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7751	7.8425	0.8759	0.7546	162.6630
CNY	0.1476		1.1575	0.1293	0.1114	24.0089
HKD	0.1275	0.8639		0.1117	0.0962	20.7412
EUR	1.1417	7.7350	8.9536		0.8615	185.7096
GBP	1.3252	8.9784	10.3929	1.1607		215.5619
JPY	0.0061	0.0417	0.0482	0.0054	0.0046	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*