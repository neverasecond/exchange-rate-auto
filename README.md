# 汇率数据自动更新（美元基准）

**更新时间**：2026-05-07 23:59:48（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.8009	7.8306	0.8498	0.7348	156.4890
CNY	0.1470		1.1514	0.1250	0.1080	23.0100
HKD	0.1277	0.8685		0.1085	0.0938	19.9843
EUR	1.1767	8.0029	9.2146		0.8647	184.1480
GBP	1.3609	9.2554	10.6568	1.1565		212.9682
JPY	0.0064	0.0435	0.0500	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*