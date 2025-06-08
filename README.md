# 221549103-
项目概述：
这段Python代码是一个Jupyter Notebook脚本，用于对名为"study.xlsx"的学生数据集进行初步分析和可视化。代码主要执行以下功能：
数据加载和概览，数据清洗和预处理，异常值检测，基本统计分析

环境配置：
所需软件：Python 3.x/Jupyter Notebook
依赖库：pandas,numpy,matplotlib,seaborn,scipy 可以使用以下命令：pip install pandas numpy matplotlib seaborn scipy

数据文件：
代码需要读取名为"study.xlsx"的Excel文件，其中包含学生相关数据。请确保该文件与Jupyter Notebook文件在同一目录下，或者修改文件路径以指向正确的位置。

使用说明：
1.将代码复制到Jupyter Notebook的单元格中
2.确保"study.xlsx"数据文件位于正确路径
3.按顺序运行所有代码单元格

代码结构说明：
1.数据加载与概览：使用pandas读取Excel文件，显示数据集形状和前5行数据，展示描述性统计信息
2.数据预处理：检查缺失值，转换分类变量为category类型，使用箱线图检测关键变量的异常值
3.可视化：使用matplotlib进行数据可视化
