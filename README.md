# Machine learning for finance 

FIN-418 Machine learning for finance is an EPFL graduate course, lectured by Prof. Ackerer.
The objective of this course is to introduce machine learning techniques for financial applications such as derivatives pricing, model calibration, portfolio allocation and hedging, investment decision, and risk-management.

The assessment method was based on the programming project available on this repository.

It was co-realized with [Tomas Giro](https://github.com/girotomas).

### Abstract —
We investigate if we can find causation relations between deposits to, and withdrawals from exchanges’ wallets, and volatility of ERC-20 tokens (more precisely ZRX, THETA and ENJ).We find no significant evidence of predictability of volatility with linear models (OLS) and non-linear ones (Random Forest). We find significance in the predictability power of transactions from and to exchanges (for the Theta and Enjin tokens only) and bitcoin prices to predict volatility, with regressive ARIMA models.


[Data prepocessing viewer](https://nbviewer.jupyter.org/github/vmeylan/machine_learning_for_finance/blob/master/notebooks/data_preprocessing.ipynb)

[Data analysis viewer](https://nbviewer.jupyter.org/github/vmeylan/machine_learning_for_finance/blob/master/notebooks/data_analysis/data_analysis_ZRX.ipynb)

Data analysis and fitting of models available in machine_learning_for_finance/notebooks/data_analysis

To run the analysis independently of GitHub, use this [link](https://colab.research.google.com/drive/1GpoQFGftNHBXgzQrt0YsQXcoZqgUZlDW)

