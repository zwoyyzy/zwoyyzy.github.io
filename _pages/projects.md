---
permalink: /projects/
title: "项目实践"
author_profile: true
---

### NIPT 最佳检测时点建模研究
主要工作：
- 通过 Pearson 相关分析、单变量回归和多元二次回归，研究孕周、BMI 等因素与胎儿 Y 染色体浓度之间的关系；
- 使用 K-means 完成 BMI 分组，结合 Kaplan–Meier 生存分析估计 Y 染色体浓度达标时间；
- 采用 Monte Carlo 随机化与 Bootstrap 重抽样处理左删失、右删失和区间删失数据；
- 在 90% 达标率目标下，为四个 BMI 分组估计推荐 NIPT 检测孕周及 95% 置信区间；
- 回归模型整体检验显著，推荐时点结果体现了不同 BMI 人群之间的检测时机差异。

**技术栈：** Python、Pandas、NumPy、scikit-learn、lifelines、SciPy、Matplotlib
