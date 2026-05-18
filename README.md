# 汇率数据自动更新（美元基准）

**更新时间**：2026-05-19 00:42:36（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7995	7.8313	0.8580	0.7447	158.9030
CNY	0.1471		1.1517	0.1262	0.1095	23.3698
HKD	0.1277	0.8682		0.1096	0.0951	20.2908
EUR	1.1655	7.9248	9.1274		0.8679	185.2016
GBP	1.3428	9.1305	10.5160	1.1521		213.3785
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