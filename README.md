# 汇率数据自动更新（美元基准）

**更新时间**：2026-09-10 01:25:59（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6966	7.8421	0.8589	0.7375	153.5190
CNY	0.1493		1.1711	0.1283	0.1101	22.9249
HKD	0.1275	0.8539		0.1095	0.0940	19.5763
EUR	1.1643	7.7967	9.1304		0.8587	178.7391
GBP	1.3559	9.0801	10.6334	1.1646		208.1614
JPY	0.0065	0.0436	0.0511	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*