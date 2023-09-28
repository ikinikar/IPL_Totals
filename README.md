# IPL_Totals
This project attempts to predict the results of IPL matches from a Kaggle dataset(https://www.kaggle.com/code/akashdubey022/data-analysis-and-prediction-of-ipl/notebook). The model considers the toss winner, which team is batting first, which team is chasing, and what the batting first total is. In its current state, the model achieves 56-62% accuracy.

Latest Version: 
IPLTotals_InPyTorch.ipynb --> The program uses PyTorch and improves on the Keras version of the model, using data standardization and slightly better-tuned hyper-parameters (and the additional usage of weight_decay) to achieve more consistent results with higher accuracy.

Older Version:
Real_IPLTotals_v2.ipynb --> The program used Keras and achieved 54-60% on the dataset somewhat inconsistently. 

Potential for future improvements: Both versions are still clearly overfitting with validation loss lagging far behind the training loss. I suspect that the small dataset size along with varying counts of how many matches teams have played is partially responsible for the overfitting (in which case following up will involve possibly creating new data/data augmentation). 
