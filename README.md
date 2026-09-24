# 汇率数据自动更新（美元基准）

**更新时间**：2026-09-24 14:57:46（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7119	7.8432	0.8780	0.7550	158.3990
CNY	0.1490		1.1686	0.1308	0.1125	23.5997
HKD	0.1275	0.8558		0.1119	0.0963	20.1957
EUR	1.1390	7.6445	8.9330		0.8599	180.4089
GBP	1.3245	8.8899	10.3883	1.1629		209.8000
JPY	0.0063	0.0424	0.0495	0.0055	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*