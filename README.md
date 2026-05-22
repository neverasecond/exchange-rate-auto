# 汇率数据自动更新（美元基准）

**更新时间**：2026-05-23 00:16:00（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7940	7.8354	0.8613	0.7441	159.2020
CNY	0.1472		1.1533	0.1268	0.1095	23.4327
HKD	0.1276	0.8671		0.1099	0.0950	20.3183
EUR	1.1610	7.8881	9.0972		0.8639	184.8392
GBP	1.3439	9.1305	10.5300	1.1575		213.9524
JPY	0.0063	0.0427	0.0492	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*