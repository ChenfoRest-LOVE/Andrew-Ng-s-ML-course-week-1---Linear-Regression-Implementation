# week-1---Linear-Regression-Implementation
吴恩达机器学习课程第一周总结  
本项目是吴恩达机器学习课程第一周内容的总结与代码实现。

## 课程内容概述
- **机器学习定义与应用**
- **监督学习与无监督学习**
- **单变量线性回归**
- **梯度下降优化**

## 关键概念

### 一. 机器学习的定义
Tom Mitchell：如果一个计算机程序在任务 T 上的性能 P 能通过经验 E 提高，则该程序从经验 E 中学习。

### 二. 学习类型：
1. **监督学习**：训练数据包含输入和正确输出。典型任务包括回归与分类。
2. **无监督学习**：训练数据无标签，目标是发现数据结构，例如聚类。

### 三. 线性回归
1. **模型公式**：预测值 = θ₀ + θ₁x
2. **代价函数**：J(θ) = (1/2m) ∑(h(x) - y)²  
   目标是最小化代价函数，找到最优参数 θ。

### 四. 梯度下降
**参数更新公式**：
- θ₀ ← θ₀ - α(1/m)∑(h(x) - y)
- θ₁ ← θ₁ - α(1/m)∑(h(x) - y) * x

其中，α 为学习率。

## 数学基础
- **线性代数**：向量、矩阵、乘法、转置、单位矩阵
- **微积分**：偏导数、梯度计算

## 线性回归实现
实现了单变量线性回归并使用梯度下降优化，主要步骤包括：
- 加载与预处理数据
- 特征归一化（可选）
- 梯度下降
- 模型评估
- 可视化结果等

## 代码部分说明
- 单变量线性回归实现的代码部分参考了吴恩达课程的 lab 并由我独立完成。
- 工具函数模块则参考了社区中的许多前辈学长，并在 GPT 辅助下完成。

## 版权声明：
本代码是根据吴恩达教授在 Coursera 上的《机器学习》课程的学习成果创建的。该课程的所有内容（包括代码、图表、模型等）都属于其原作者（Andrew Ng）及其所在的机构，除非获得授权，否则不得用于商业目的或转售。任何在此基础上修改或分发的代码，应附带适当的来源声明，并遵守 Coursera 以及相关资源的版权条款。

## 声明：
该项目/代码由 [ChenfoRest-LOVE] 创建，旨在记录自己在机器学习课程中所获得的收获和心得。如果您发现任何错误或有任何建议，请通过以下方式与我联系：[chenbingqi0@gmail.com]。欢迎提出宝贵意见，本项目内容并非完美无缺，若有任何地方需要改进或优化，请不吝指正。感谢您的支持与反馈！

## 再次感谢您的支持！
