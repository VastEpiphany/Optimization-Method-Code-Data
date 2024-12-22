# Optimization-Method-Code-Data
这是2024优化方法课程对应代码和附件、处理数据的存储仓库

## 文件说明：
以下是仓库中各文件的功能说明：

### 代码文件
- **Data_manipulation.ipynb**  
  包含数据的预处理与特征工程操作，如缺失值填补、数据标准化和特征选择。  

- **Repay_Prob_cal&Loss_cal.ipynb**  
  实现了企业违约概率的计算模型，包括逻辑回归、随机森林和XGBoost模型的训练和评估，同时计算了相应的流失损失函数。

- **Solution.ipynb**  
  提供了优化模型的完整求解过程，基于混合整数非线性规划（MINLP）问题，计算最优的放贷策略。

- **final_plot.ipynb**  
  包含最终可视化结果的生成代码，包括违约概率分布图和贷款金额分布的3D柱状图。

- **poly_rate_fitting.ipynb**  
  用于拟合流失率函数的多项式曲线，根据企业信用评级和贷款利率构建非线性函数。

### 其他文件
- **File1.xlsx**  
  附件1，包含123家企业的企业信息、进项及销项发票信息。

- **File2.xlsx**
  附件2，包含各个不同评级间的企业在不同贷款利率下的客户流失率数据。

- **final_merged_data_with_predictions&loss.xlsx**
  得到的对应违约概率的估计数据以及所使用到的各个企业的自变量数据的整合。

- **updated_loan_decision_result_with_fluctuations.xlsx**
  最终放贷决策数据。
