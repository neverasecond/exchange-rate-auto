# 汇率数据自动更新（美元基准）

**更新时间**：2026-11-07 04:09:39（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6755	7.8389	0.8974	0.7489	158.5200
CNY	0.1498		1.1743	0.1344	0.1122	23.7465
HKD	0.1276	0.8516		0.1145	0.0955	20.2222
EUR	1.1143	7.4387	8.7351		0.8345	176.6436
GBP	1.3353	8.9137	10.4672	1.1983		211.6704
JPY	0.0063	0.0421	0.0495	0.0057	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*