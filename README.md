# 汇率数据自动更新（美元基准）

**更新时间**：2026-05-21 00:45:44（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.8005	7.8326	0.8598	0.7437	158.8240
CNY	0.1470		1.1518	0.1264	0.1094	23.3548
HKD	0.1277	0.8682		0.1098	0.0949	20.2773
EUR	1.1631	7.9094	9.1098		0.8650	184.7220
GBP	1.3446	9.1441	10.5319	1.1561		213.5592
JPY	0.0063	0.0428	0.0493	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*