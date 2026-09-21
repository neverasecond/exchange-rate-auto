# 汇率数据自动更新（美元基准）

**更新时间**：2026-09-22 02:58:47（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6948	7.8448	0.8720	0.7480	157.4750
CNY	0.1494		1.1718	0.1303	0.1117	23.5220
HKD	0.1275	0.8534		0.1112	0.0953	20.0738
EUR	1.1468	7.6775	8.9963		0.8578	180.5906
GBP	1.3369	8.9503	10.4877	1.1658		210.5281
JPY	0.0064	0.0425	0.0498	0.0055	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*