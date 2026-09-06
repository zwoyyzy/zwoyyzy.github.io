---
permalink: /projects/
title: "项目实践"
author_profile: true
---

### 基于文本与图像多模态融合的脊柱分割｜进行中

本科生科研训练项目，已立项国家级，尝试将文本语义信息引入脊柱 MRI 图像分割，以改善边界模糊、小样本结构及类别不均衡场景下的分割表现。

- 调研 U-Net、Swin-UMamba 等医学图像分割模型，尝试复现并建立基线；
- 探索全局解剖描述与像素级类别提示相结合的 Dual-Prompt 机制；
- 尝试通过交叉注意力融合视觉与文本特征，增强模型对椎体、椎间盘等结构的识别；
- 计划在 SPIDER、MRSpineSeg 数据集上开展对比与消融实验，并使用 DSC、HD95 等指标进行评估。

**技术栈（计划）：** Python、PyTorch、MONAI、Swin-UMamba、BERT、医学图像分割

### NIPT 最佳检测时点建模研究｜2025 CUMCM
主要工作：
- 通过 Pearson 相关分析、单变量回归和多元二次回归，研究孕周、BMI 等因素与胎儿 Y 染色体浓度之间的关系；
- 使用 K-means 完成 BMI 分组，结合 Kaplan–Meier 生存分析估计 Y 染色体浓度达标时间；
- 采用 Monte Carlo 随机化与 Bootstrap 重抽样处理左删失、右删失和区间删失数据；
- 在 90% 达标率目标下，为四个 BMI 分组估计推荐 NIPT 检测孕周及 95% 置信区间；
- 回归模型整体检验显著，推荐时点结果体现了不同 BMI 人群之间的检测时机差异。

**技术栈：** Python、Pandas、NumPy、scikit-learn、lifelines、SciPy、Matplotlib


### 舞蹈竞演节目投票机制优化｜2026 MCM/ICM

基于《Dancing with the Stars》历史数据，分析评委评分与观众投票的差异，并设计兼顾公平性与节目悬念的新型赛制。

- 基于 **Dirichlet 分布与拒绝采样**反推观众投票比例，淘汰结果匹配率达到 **99.63%**；
- 使用 **Spearman 相关分析**比较排名制与百分比制，评估不同赛制对争议选手的影响；
- 结合 **OLS 与随机森林回归**，分析年龄、职业舞伴等特征对评委评分和观众投票的影响；
- 设计“评分校准、票数压缩、动态权重与末位裁决”机制，通过网格搜索与历史回测优化参数，使强者误淘汰率降低约 **14%**。

**技术栈：** Python、Pandas、NumPy、Scikit-learn、Statsmodels、Matplotlib
