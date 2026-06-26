# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-26 14:02:12（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7998	7.8410	0.8787	0.7574	161.5940
CNY	0.1471		1.1531	0.1292	0.1114	23.7645
HKD	0.1275	0.8672		0.1121	0.0966	20.6089
EUR	1.1380	7.7385	8.9234		0.8620	183.9012
GBP	1.3203	8.9778	10.3525	1.1602		213.3536
JPY	0.0062	0.0421	0.0485	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*