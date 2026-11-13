# 汇率数据自动更新（美元基准）

**更新时间**：2026-11-13 16:54:58（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6700	7.8455	0.9039	0.7555	159.8980
CNY	0.1499		1.1762	0.1355	0.1133	23.9727
HKD	0.1275	0.8502		0.1152	0.0963	20.3809
EUR	1.1063	7.3791	8.6796		0.8358	176.8979
GBP	1.3236	8.8286	10.3845	1.1964		211.6453
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