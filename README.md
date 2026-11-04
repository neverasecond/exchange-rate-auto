# 汇率数据自动更新（美元基准）

**更新时间**：2026-11-05 04:36:27（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.6731	7.8453	0.8901	0.7421	158.4400
CNY	0.1499		1.1757	0.1334	0.1112	23.7431
HKD	0.1275	0.8506		0.1135	0.0946	20.1955
EUR	1.1235	7.4970	8.8140		0.8337	178.0025
GBP	1.3475	8.9922	10.5718	1.1994		213.5022
JPY	0.0063	0.0421	0.0495	0.0056	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*