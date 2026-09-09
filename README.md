# 汇率数据自动更新（美元基准）

**更新时间**：2026-09-09 14:54:24（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7066	7.8421	0.8590	0.7376	153.3050
CNY	0.1491		1.1693	0.1281	0.1100	22.8588
HKD	0.1275	0.8552		0.1095	0.0941	19.5490
EUR	1.1641	7.8075	9.1293		0.8587	178.4692
GBP	1.3557	9.0925	10.6319	1.1646		207.8430
JPY	0.0065	0.0437	0.0512	0.0056	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*