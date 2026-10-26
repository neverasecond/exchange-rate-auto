# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-27 03:39:33（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6593	7.8453	0.8940	0.7491	157.4520
CNY	0.1502		1.1781	0.1342	0.1125	23.6439
HKD	0.1275	0.8488		0.1140	0.0955	20.0696
EUR	1.1186	7.4489	8.7755		0.8379	176.1208
GBP	1.3349	8.8897	10.4730	1.1934		210.1882
JPY	0.0064	0.0423	0.0498	0.0057	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*