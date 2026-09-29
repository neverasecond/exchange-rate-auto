# 汇率数据自动更新（美元基准）

**更新时间**：2026-09-30 02:59:48（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6987	7.8462	0.8815	0.7559	157.2030
CNY	0.1493		1.1713	0.1316	0.1128	23.4677
HKD	0.1275	0.8538		0.1123	0.0963	20.0356
EUR	1.1344	7.5992	8.9010		0.8575	178.3358
GBP	1.3229	8.8619	10.3799	1.1662		207.9680
JPY	0.0064	0.0426	0.0499	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*