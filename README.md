# Multi Armed Bandit for Credit Risk

Herein a Multi armed bandit (MAB) is used for credit risk. Since the formulation of the MAB for the proposed environment is challenging, DT is used to cluseter customer through their credit data. And each cluster is considered as an arm with an independent and seperable reward distribution. For the MAB 
implementation, four algorithms are used: Greedy algorithm, Epsilon Greedy algorithm with Epsilon as 0.1 and 0.01, Upper Confidence Bound with C as 1 and 2 and Thompson Sampling

The evaluation is done through threeways:
1) Algorithms are compared based on cumulative reward
2) Algorithms are compared based on the profit they generate for the financial institution
3) Finally the best performing algorithms are compared with Logisitic Regression on the basis of the profit


For this research, three datasets were used and the py files are named based on the dataset. The datasets can be downloaded from the following links:
- Creditcardfraud : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?resource=download
- Australian : https://archive.ics.uci.edu/ml/datasets/statlog+(australian+credit+approval)
- German : https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data)
