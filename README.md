# 汇率数据自动更新（美元基准）

**更新时间**：2026-09-25 02:04:25（北京时间）

## Excel 表格（制表符分隔）

Currency	USD	CNY	HKD	EUR	GBP	JPY
USD		6.7028	7.8427	0.8800	0.7572	158.9880
CNY	0.1492		1.1701	0.1313	0.1130	23.7196
HKD	0.1275	0.8547		0.1122	0.0965	20.2721
EUR	1.1364	7.6168	8.9122		0.8605	180.6682
GBP	1.3207	8.8521	10.3575	1.1622		209.9683
JPY	0.0063	0.0422	0.0493	0.0055	0.0048	

## CSV 文件链接

https://raw.githubusercontent.com/granthuang999/exchange-rate-auto/main/exchange_rates.csv

### 数据源说明
- 优先使用 Yahoo Finance 实时汇率
- Yahoo 失败时使用 Wise 汇率
- 最后备选 ExchangeRate-API
- 以美元为基准计算所有交叉汇率

---
*数据仅供参考，交易请以银行报价为准*