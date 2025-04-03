# 数据可视化实战指南：从基础图表到高级分析

**文档概要**：  
本文档系统整理数据可视化核心方法，涵盖Excel与Tableau两大工具的实战应用。内容包含17种基础图表制作技巧（柱形图、折线图、饼图等）、10类高级分析模型（子弹图、漏斗图、动态气泡图等），以及福特汽车销售分析、超市销售地理可视化等企业级案例解析。适合数据分析师及商业智能从业者快速掌握可视化关键技能。

---


# 1. Excel 数据可视化
## 1.4 绘制表格数据的百分比堆积柱形图  
![image](https://github.com/user-attachments/assets/2dac7cbe-19d5-4022-8599-01e26786d28d)

**总结**：  
用百分比展示数据占比关系，适合分析多类别数据的比例分布。

## 1.5 绘制表格数据的折线图  
![image](https://github.com/user-attachments/assets/bd62e490-c4f8-42a8-bdcd-61ebdd7f78c4)

**总结**：  
优化折线图清晰度：编辑数据源 -> 设置标记样式（圆形、纯色填充）。通过数据系列格式调整标记颜色和大小。

## 1.6 绘制表格数据的折线图，包括标题、系列名称，并标出数据点
![image](https://github.com/user-attachments/assets/72c57914-f424-4944-9f98-e1454a1c660f)

**总结**：  
面积图可突出总值变化，折线图需补充标题和系列名称，并通过数据标签功能显示具体数值点。

## 1.7 绘制表格数据的面积图  
![image](https://github.com/user-attachments/assets/0504500d-e4d1-4c34-8ced-099771f190b3)

**总结**：  
面积图适合展示数据随时间变化的累积趋势，强调总量而非单个数值。

## 1.8 绘制表格数据的圆饼图，并设置合适的扇区位置  
![image](https://github.com/user-attachments/assets/960d4b94-31e6-4521-b6da-b5223162c395)

**总结**：  
饼图数据需避免负值或接近0的值。调整扇区位置：双击扇区 -> 系列选项 -> 设置第一扇区起始角度（如240°）。

## 1.9 绘制表格数据的圆饼图，并突出强调洗衣机的扇区，使其显示在图表左边区域  
![image](https://github.com/user-attachments/assets/af02ace0-d877-464e-a404-655197b0da1b)

**总结**：  
通过分离扇区（如22%）和调整起始角度（如53°），将目标扇区定位至左侧突出显示。

## 1.10 绘制表格数据的圆饼图和半个圆饼图  
![image](https://github.com/user-attachments/assets/77eaa77c-ba6c-423e-adb2-a67a13618039)

**总结**：  
制作半圆饼图需添加总计数据行，将总计扇区填充设置为白色或无填充，起始角度设为270°。

## 1.11 绘制表格数据的堆积圆饼图  
![image](https://github.com/user-attachments/assets/e92b3ea0-a586-4cda-ad2a-a07782849aee)

**总结**：  
堆积圆饼图通过层叠对比增强数据差异，优于分散的多饼图对比。可通过三维样式优化视觉效果。

## 1.12 绘制表格数据的散点图、带平滑线和数据标记的散点图  
![image](https://github.com/user-attachments/assets/48faa843-e42c-474b-97be-569ef6745534)

**总结**：  
散点图适合零散数据点分析，添加平滑线可增强趋势连续性。路径：推荐图表 -> XY散点图 -> 带平滑线的散点图。

## 1.13 绘制表格数据的气泡图，并将直角坐标改为象限坐标  
![image](https://github.com/user-attachments/assets/8dce7053-231f-4346-a32b-748e0d158d13)

**总结**：  
气泡图增加第三维度（气泡大小）。设置象限坐标：双击纵坐标轴 -> 横坐标轴交叉设为0.65。通过单元格值添加数据标签。

## 1.14 绘制表格数据的子弹图  
![image](https://github.com/user-attachments/assets/6241633b-a279-4729-80df-c458e73474b8)

**总结**：  
子弹图对比计划与实际值，制作方法：  
1. 插入堆积柱形图 -> 实际序列设为次坐标轴  
2. 更改图表类型为带直线的散点图  
3. 设置标记为短横线（大小15）

## 1.15 绘制表格数据的温度计图  
![image](https://github.com/user-attachments/assets/1af02f23-30f1-40c8-ae30-203fe2053872)

**总结**：  
温度计图显示进度完成率：  
1. 设置柱形分类间距为0  
2. 纵坐标最大值1.0，主要刻度0.1  
3. 红色填充已完成部分，黑色填充未完成部分

## 1.16 绘制表格数据的漏斗图  
![image](https://github.com/user-attachments/assets/3c714bb9-797c-4c17-99bd-4d1c32c22164)

**总结**：  
漏斗图展示业务流程各阶段转化率，适合分析用户流失环节。

## 1.17 根据福特公司2019年上半年的销售情况，分别用直方图、折线图、饼图绘制分析数据，并简单分析  
![image](https://github.com/user-attachments/assets/b0c10a69-bda9-453e-bf87-d5c614e1ca5d)

**总结**：  
直方图分析销量分布，折线图追踪月度趋势，饼图展示车型销售占比，三图结合全面反映销售特征。

# 2. 基于 Tableau 的某超市销售数据报告
## 2.1 各省销售额和类别堆积条形图  
![image](https://github.com/user-attachments/assets/64e5a353-c509-48ba-9597-629227a09daf)

**总结**：  
堆积柱形图多维展示数据比例，比饼图承载更多信息维度，比散点图更直观。

## 2.2 各类别销售量直方图  
![image](https://github.com/user-attachments/assets/9a877a85-2d10-4906-8f8e-aca923e61b5e)

**总结**：  
直方图清晰显示众数（0k）、中位数（约4k）及异常值（18k-24k区间缺失）。

## 2.3 不同类别商品销售额饼图  
![image](https://github.com/user-attachments/assets/5652e6f6-2a5b-4106-bf5d-91f8c33d3bfa)

**总结**：  
饼图直观展示品类占比，但类别超过5项时建议改用条形图。

## 2.4 月销售额趋势折线图  
![image](https://github.com/user-attachments/assets/2c52ca1c-f983-4dae-9c50-eeb2bdfa0568)

**总结**：  
折线图揭示7月下降、8月峰值、10-12月平缓的周期性特征。

## 2.5 各省利润突显表  
![image](https://github.com/user-attachments/assets/ffd6352b-0508-4bef-86bd-13c2fc0761a2)

**总结**：  
用橙黄色高亮负利润，深蓝色强调高利润，快速识别异常省份。

## 2.6 各省销售额和利润树形图  
![image](https://github.com/user-attachments/assets/da0377fd-675f-4fca-9c18-07319ec17b22)

**总结**：  
树形图以面积大小表示销售额，颜色深浅表示利润率，揭示山东高销高利、辽宁高销低利的差异。

## 2.7 各省销售额气泡图  
![image](https://github.com/user-attachments/assets/e2061fb1-8397-4a1e-a039-ee7c1458f737)

**总结**：  
气泡图三维展示销售额（X轴）、利润（Y轴）、销售量（气泡大小），综合评估省份绩效。

## 2.8 各子类别在各省市的销售额圆视图  
![image](https://github.com/user-attachments/assets/2c466b09-9c85-4e6e-b54b-3053be5bb11e)

**总结**：  
圆视图有序排列子类别气泡，突显山东书架销售额异常值。

## 2.9 各省销售计划完成情况标靶图  
![image](https://github.com/user-attachments/assets/11ece598-d97e-4277-b809-c69da2866f6a)

**总结**：  
标靶图通过参考线（计划值）和参考区间（容差范围）快速评估完成度。

## 2.10 2016年各省商品交货情况的甘特图  
![image](https://github.com/user-attachments/assets/1950199a-1f3d-41ac-a90a-4d289b234ea9)

**总结**：  
甘特图显示安徽延迟交货最少，11-12月全国延迟率上升。

## 2.11 各地区平均销售额统计的盒须图、各地区酒店不同价格统计的盒须图  
![image](https://github.com/user-attachments/assets/56111098-26e8-4b76-b8e2-09f98558256d)

**总结**：  
盒须图显示沙田、离岛数据集中，油尖旺存在高价异常值。

## 2.12 不同子类别盈亏的瀑布图  
![image](https://github.com/user-attachments/assets/bc2bedf3-2d26-47b3-a65d-998d9adf76bc)

**总结**：  
瀑布图解释利润差异构成，但适用场景单一，主要用于解释两个总值差异。

## 2.13 流量转化漏斗图  
![image](https://github.com/user-attachments/assets/a236ca53-24de-488f-8ab7-1116d44550d1)

**总结**：  
漏斗图显示公众号访问-关注阶段流失率最高（40%），客服咨询-成交阶段流失率最低（8%）。

## 2.14 不同子类别利润凹凸图  
![image](https://github.com/user-attachments/assets/a859ad39-200a-4573-b958-ced751f0924a)

**总结**：  
凹凸图反映桌子利润排名稳定，附件排名波动剧烈的竞争态势。

## 2.15 各省市销售量和利润的符号地图  
![image](https://github.com/user-attachments/assets/77de3062-f480-48eb-958a-bec369fbc4c2)

**总结**：  
符号地图用点大小（利润）和颜色深浅（销售额）双维度展示地理分布。

## 2.16 喜剧、剧情、爱情、动作电影动态气泡图 
![image](https://github.com/user-attachments/assets/c932de76-6c5e-40fd-a64f-7da650cd53e3)

**总结**：  
动态气泡图结合时间轴，展示电影类型票房、评分、投资回报率的年度变化。

# 3. 实验三
## 3.1 仪表板  
![image](https://github.com/user-attachments/assets/7b39dd29-10d3-40d2-89b4-7986941c5ce2)

**总结**：  
通过类别筛选器（纸张/配件/装订机/复印件）联动条形图和压力图，发现山东、广东为销售重点区域。

## 3.2 符号地图  
![image](https://github.com/user-attachments/assets/83fbc163-97d9-40c3-a7bc-9c9dfe2d6e59)

**总结**：  
符号地图用点大小编码销售额，空间维度揭示沿海省份销售优势。

## 3.3 填充地图  
![image](https://github.com/user-attachments/assets/793b3c7b-b3ec-4ec6-8506-22bc5530338b)

**总结**：  
填充地图用颜色渐变展示销售额梯度，快速识别高潜力区域。

## 3.4 多维地图  
![image](https://github.com/user-attachments/assets/4c6a93fc-1954-4bc2-b2f7-82fd5a0e3a1a)

**总结**：  
多维地图叠加时间和品类维度，分析不同时期各类商品区域销售特征。

## 3.5 混合地图  
![image](https://github.com/user-attachments/assets/4d9fb0d2-1ccb-41d3-947f-fd422aac9893)

**总结**：  
混合地图结合符号（利润）和填充（销售额），实现双指标地理空间分析。
