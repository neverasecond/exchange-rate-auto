# 汇率数据自动更新（美元基准）

**更新时间**：2026-09-22 15:04:22（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6991	7.8435	0.8722	0.7480	157.6740
CNY	0.1493		1.1708	0.1302	0.1117	23.5366
HKD	0.1275	0.8541		0.1112	0.0954	20.1025
EUR	1.1465	7.6807	8.9928		0.8576	180.7773
GBP	1.3369	8.9560	10.4860	1.1660		210.7941
JPY	0.0063	0.0425	0.0497	0.0055	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*