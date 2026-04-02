# Supply-chain-data-analysis
使用 Python（pandas、numpy、matplotlib、plotly、seaborn）进行数据分析

项目概述
本项目旨在分析供应链数据，以评估产品性能、库存水平和运营效率。
目标是优化库存分配并改进供应链决策。

数据集
来源：供应链数据集（模拟/基于 Kaggle）
关键字段：
订单详情:Product type、SKU、Price、Availability、Number of products sold、Revenue generated、Customer demographics。
库存及运输数据：Stock levels、Lead times、Order quantities、Shipping times、Shipping carriers、Shipping costs、Supplier name、Location、Lead time、Production volumes、Manufacturing、lead time、Manufacturing costs、Inspection results、Defect rates、Transportation modes、Routes、Costs 

工具与技术
Python（Pandas、NumPy）
可视化：Plotly / Seaborn / matplotlib 

分析流程
数据清洗
标准化列格式
数据转换
按 SKU 汇总数据
计算总收入、库存和订单量
探索性数据分析
按收入排名的前几大 SKU
库存与需求对比
成本和交货周期分析

关键问题
本分析旨在回答以下问题
热门产品：收入最高的10种产品是什么？
区域业绩：各区域销量排名前 5 的产品是什么？
销售增长：2022 年和 2023 年的月度销售增长情况如何？
类别表现：每个类别中，哪个月份的销售额最高？
利润增长：与 2022 年相比，2023 年哪个子类别的利润增长最高？

关键洞察
某些 SKU（例如 SKU32、SKU0）贡献了大部分收入
部分产品库存高但销量相对较低 → 效率低下
不同供应商的交货周期差异显著

业务建议
增加高需求 SKU 的库存分配
减少滞销产品的库存
根据交货时间和成本优化供应商选择

结论
本项目重点阐述了供应链分析如何通过数据驱动的洞察来改善库存管理和运营效率。


建议
聚焦畅销产品：将更多资源投入到营收排名前十的产品，例如 TEC-PH-10003645 和 FUR-CH-10000454，以实现利润最大化。区域优化：根据区域偏好调整营销策略。例如，TEC-PH-10003645 在南部和西部地区均表现优异。季节性促销：利用月度增长数据洞察，制定季节性促销计划。例如，家具和办公用品分别在三月和五月表现突出。品类拓展：投资于家具和科技等高绩效品类，以推动进一步增长。利润最大化：专注于利润增长最快的子品类，例如科技产品，以确保持续盈利。

结论
本项目展示了我运用 Python 和 SQL 提取、转换和分析大型数据集的能力。通过挖掘销售业绩、区域趋势和利润增长的关键洞察，我提出了切实可行的建议来优化业务运营。我精通数据分析，并熟练掌握 Python、SQL 和数据库管理，这使我成为任何组织中数据驱动型岗位的理想人选。本项目充分展现了我将原始数据转化为能够推动业务成功的有意义的洞察的能力
