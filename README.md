# 宏观经济数据时间序列分析 (HW2)

本项目主要是对中美两国的宏观经济数据进行统计分析与建模。

## 项目结构
* `data/`: 包含中国 (`DATACN.xlsx`) 和美国 (`DATAUS.xlsx`) 的原始数据集。
* `HW2.ipynb`: 数据清洗、探索性数据分析 (EDA) 以及模型构建的 Jupyter Notebook 源文件。
* `report/`: 包含 LaTeX 编写的最终分析报告 (`HW2.tex`) 及相关可视化图表 (`figure/`)。
* `tools/`: 包含用于季节性调整的 X-13ARIMA-SEATS 可执行程序。

## 使用方法
1. 克隆本项目到本地。
2. 确保安装了 Jupyter 环境及相关数据科学库 (如 `pandas`, `statsmodels` 等)。
3. 运行 `HW2.ipynb` 查看完整的分析推导过程。
