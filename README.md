# Supply-chain-data-analysis
使用 Python（pandas、numpy、matplotlib、plotly、seaborn）进行数据分析

## 项目概述
本项目旨在分析供应链数据，以评估产品性能、库存水平和运营效率。
目标是优化库存分配并改进供应链决策。

## 数据集
来源：供应链数据集（模拟/基于 Kaggle）
关键字段：
订单详情:Product type、SKU、Price、Availability、Number of products sold、Revenue generated、Customer demographics
库存及运输数据：Stock levels、Lead times、Order quantities、Shipping times、Shipping carriers、Shipping costs、Supplier name、Location、Lead time、Production volumes、Manufacturing、lead time、Manufacturing costs、Inspection results、Defect rates、Transportation modes、Routes、Costs 

## 工具与技术
Python（Pandas、NumPy）
可视化：Plotly / Seaborn / matplotlib 

## 分析流程
数据清洗
标准化列格式
数据转换
按SKU汇总收入、库存和利润
运输方式分析
成本和交货周期分析

## 关键问题
本分析旨在回答以下问题
热门产品：收入最高的10种SKU是什么？与高利润的10种SKU是否匹配？与高库存SKU是否匹配？是否存在库存高销量低的产品？
客户结构：公司在哪些群体的平均收入更高？
定价分析：公司在护肤品、护发品和化妆品三大产品类型的价格范围？
运输分析：海运、空运、铁路、公路四种运输方式的运输成本、运输时间、不良率？
供应商分析：不同供应商的交货时间和运输成本的差别？

## 建议
1.聚焦畅销产品：将更多资源投入到营收排名前十的产品，例如SKU32、SKU98、SKU0、SKU88等，以实现利润最大化。并相应的减少高库存低销量产品的库存，例如SKU91、SKU46、SKU59等，优化库存周转率，加快资金和商品的流动。
2.针对性营销：根据客户结构和公司在不同群体的平均收入进行针对性营销，例如公司的客户群体有未知性别群体、女性、非二元性别和男性，平均收入最高的是女性群体，因此可以进行针对性营销活动。
3.灵活选择运输方式：海运、空运、铁路、公路四种运输方式的运输成本、运输时间、不良率不同，综合来看路线A和路线C的公路运输综合最优，提升供应链效率。
4.供应商选择：不同供应商的交货时间和运输成本不同，综合来看，选择供应商1和供应商4，有利于降低供应链成本。

## 结论
本项目展示了我运用 Python（pandas、numpy、matplotlib、plotly、seaborn） 分析数据的能力。通过挖掘热门产品、客户结构、运输方式和供应商的关键洞察，提出了切实可行的建议来优化业务运营。精通数据分析，并熟练掌握 Python，本项目充分展现了我将原始数据转化为能够推动业务成功的有意义的洞察的能力
