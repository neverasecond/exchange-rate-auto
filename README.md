# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-08 00:19:14（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7838	7.8423	0.8754	0.7480	161.9130
CNY	0.1474		1.1560	0.1290	0.1103	23.8676
HKD	0.1275	0.8650		0.1116	0.0954	20.6461
EUR	1.1423	7.7494	8.9585		0.8545	184.9589
GBP	1.3369	9.0693	10.4844	1.1703		216.4612
JPY	0.0062	0.0419	0.0484	0.0054	0.0046	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*