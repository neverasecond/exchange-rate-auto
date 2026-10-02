# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-02 15:45:38（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6987	7.8459	0.8881	0.7570	157.7080
CNY	0.1493		1.1713	0.1326	0.1130	23.5431
HKD	0.1275	0.8538		0.1132	0.0965	20.1007
EUR	1.1260	7.5427	8.8345		0.8524	177.5791
GBP	1.3210	8.8490	10.3645	1.1732		208.3329
JPY	0.0063	0.0425	0.0497	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*