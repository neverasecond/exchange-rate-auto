# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-23 13:17:05（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7677	7.8404	0.8745	0.7472	163.0860
CNY	0.1478		1.1585	0.1292	0.1104	24.0977
HKD	0.1275	0.8632		0.1115	0.0953	20.8007
EUR	1.1435	7.7389	8.9656		0.8544	186.4906
GBP	1.3383	9.0574	10.4930	1.1704		218.2628
JPY	0.0061	0.0415	0.0481	0.0054	0.0046	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*