# 图表的分类
- Trends/趋势图
 - sns.lineplot - Line charts/折线图
 
- Relationship/关系图
 - sns.barplot - Bar chars/柱状图， 通过量化比较找到区别
 - sns.heatmap - Heatmaps/热力图， 通过颜色寻找模式
 - sns.scatterplot - Scatter plots/散点图， 展示两种连续性变量之间的关系，
 - sns.regplot - 包含Regression line的散点图，可以更容易找到两种变量的关系（通过回归线的斜率）
 - sns.lmplot - 包含多个回归线
 - sns.swarmplot - 分类的散点图，通过一个连续型变量和一个类型变量，展示分类信息
 
- Distribution/分布图
 - sns.distplot - Histograms/直方图， 展示单一数值型变量的分布
 - sns.kdeplot - Kernel Density Esimate/核密度估计（2D KDE）， 展示一种预估的、平滑的分布情况。
 - sns.jointplot - 同时展示一个2D KDE
