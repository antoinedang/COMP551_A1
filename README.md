ABDO ELIE-DIMITRI (260948346), DANGEARD ANTOINE (260962884), CHAI YUTING (260888064)

NOTE: This is a shortened version of the report, the complete document can be found above in .docx format

**COMP 551 MACHINE LEARNING- MINI-PROJECT 1**

_ **Abstract:** _ This study investigates the performance of two very common machine learning models — linear regression and logistic regression – on two benchmark datasets. To optimize our models, we used the closed form for linear regression, as well as gradient descent on both the logistic and linear regression models. We implemented mini-batch stochastic gradient descent with optional momentum, regularization, non-linear base function and learning rate arguments.

**DISCUSSION AND CONCLUSIONS**

The two ML models, linear regression and logistic regression, were the subject of several tests, which are fully summarised in this study. We came to the conclusion that a 50/50 split between the training set and test set results in the best performance for both logistic and linear regression models. We discovered that, when performance and convergence time were taken into account, batch sizes of 16 for linear regression and 8 for logistic regression were overall optimal. The outcomes, however, demonstrate that the full-batch linear regression still generates a lesser error than the ideal mini-batch one. Four different learning rates were used in our experimentation which concluded that smaller learning rates perform worse than learning rates between 0.6 and 1.0. Additionally, momentum resulted in more uniform errors when running the experiments multiple times with shuffled data. We have also explored the possibility that the data followed non-linear bases. This experiment proved to be successful for regression assuming polynomial bases, but not for logistic regression as the F1 scores were all lower.

One future investigation would be to use adaptive momentum estimation (Adam) to estimate the model. We could compare the model generated by the Adam approach with the gradient descent with momentum approach to see if Adam performs better.

**STATEMENT OF CONTRIBUTIONS**

Antoine Dangeard: Implemented classes for gradient descent regression, analytical linear regression, and regularized regression with non linear bases, implemented data standardization for energy efficiency dataset, implemented functions for experiments, helped with report.

Elie Dimitri-Abdo: Implemented classes for analytical linear regression and gradient descent, standardized energy efficiency dataset, implemented mini-batching for cleaned data, implemented functions for experiments, write up of the report.

Yuting Chai: Cleaned up the dataset, write up the report.
