# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-20 00:27:52（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7681	7.8365	0.8717	0.7560	161.2730
CNY	0.1478		1.1579	0.1288	0.1117	23.8284
HKD	0.1276	0.8637		0.1112	0.0965	20.5797
EUR	1.1472	7.7643	8.9899		0.8673	185.0098
GBP	1.3228	8.9525	10.3657	1.1530		213.3241
JPY	0.0062	0.0420	0.0486	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*