# 汇率数据自动更新（美元基准）

**更新时间**：2026-11-05 16:45:27（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6688	7.8450	0.8893	0.7421	158.2280
CNY	0.1500		1.1764	0.1334	0.1113	23.7266
HKD	0.1275	0.8501		0.1134	0.0946	20.1693
EUR	1.1245	7.4989	8.8215		0.8345	177.9242
GBP	1.3475	8.9864	10.5714	1.1984		213.2165
JPY	0.0063	0.0421	0.0496	0.0056	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*