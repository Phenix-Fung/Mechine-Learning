# 小米扫地机器人智能导航系统(Xiaomi Sweeping Robot Intelligent Navigation System)
## 1. 项目背景介绍

2020年，全球服务型机器人销售额达到**94.6亿美元**，同比增长**22.54%**；预计到2023年，全球服务机器人市场规模将突破**201亿美元**。  
**人工智能技术**是服务机器人获得实质性发展的重要引擎，目前正从感知智能向认知智能加速迈进。  

### 本项目的目标
本项目将聚焦于小米扫地机器人在移动清扫过程中的智能导航系统，主要任务包括：
1. 收集机器人运动轨迹数据。
2. 利用**机器学习模型**进行数据分析。
3. 智能判断移动方向，实现高效导航。

---

## 2. 数据集介绍

### 数据集结构
- 参数：`X0~X23`，包括传感器的输入（如`front`、`left`、`right`、`back`）。
- 标签：`label`，表示最终选择的移动方向。

### 数据量
- 总计：**4865行数据**。

### 技术栈
- 本项目使用 **Python** 编写代码进行数据分析与模型开发。
- 对于代码和建模过程更详细的解答在我个人CSDN博客，链接：https://blog.csdn.net/fengyaopeng/article/details/132042092?spm=1001.2014.3001.5501
