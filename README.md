# 汇率数据自动更新（美元基准）

**更新时间**：2026-07-02 00:17:55（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7784	7.8437	0.8779	0.7528	162.4030
CNY	0.1475		1.1572	0.1295	0.1111	23.9589
HKD	0.1275	0.8642		0.1119	0.0960	20.7049
EUR	1.1391	7.7212	8.9346		0.8575	184.9903
GBP	1.3284	9.0043	10.4194	1.1662		215.7319
JPY	0.0062	0.0417	0.0483	0.0054	0.0046	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*