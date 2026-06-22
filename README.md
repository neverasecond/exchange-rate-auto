# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-23 02:08:43（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7641	7.8394	0.8746	0.7550	161.4990
CNY	0.1478		1.1590	0.1293	0.1116	23.8759
HKD	0.1276	0.8628		0.1116	0.0963	20.6009
EUR	1.1434	7.7339	8.9634		0.8633	184.6547
GBP	1.3245	8.9591	10.3833	1.1584		213.9060
JPY	0.0062	0.0419	0.0485	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*