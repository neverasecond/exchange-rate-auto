# 汇率数据自动更新（美元基准）

**更新时间**：2026-10-15 02:13:36（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6867	7.8483	0.8970	0.7591	158.4270
CNY	0.1496		1.1737	0.1341	0.1135	23.6929
HKD	0.1274	0.8520		0.1143	0.0967	20.1862
EUR	1.1148	7.4545	8.7495		0.8463	176.6187
GBP	1.3173	8.8087	10.3390	1.1817		208.7037
JPY	0.0063	0.0422	0.0495	0.0057	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*