# 汇率数据自动更新（美元基准）

**更新时间**：2026-06-26 00:16:17（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7862	7.8401	0.8783	0.7568	161.6920
CNY	0.1474		1.1553	0.1294	0.1115	23.8266
HKD	0.1275	0.8656		0.1120	0.0965	20.6237
EUR	1.1386	7.7265	8.9264		0.8617	184.0966
GBP	1.3214	8.9670	10.3595	1.1605		213.6522
JPY	0.0062	0.0420	0.0485	0.0054	0.0047	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*