# 汇率数据自动更新（美元基准）

**更新时间**：2026-05-26 13:58:56（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7863	7.8349	0.8597	0.7421	159.0210
CNY	0.1474		1.1545	0.1267	0.1094	23.4327
HKD	0.1276	0.8662		0.1097	0.0947	20.2965
EUR	1.1632	7.8938	9.1135		0.8632	184.9727
GBP	1.3475	9.1447	10.5577	1.1585		214.2851
JPY	0.0063	0.0427	0.0493	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*