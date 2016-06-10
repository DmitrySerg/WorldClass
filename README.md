# WorldClass
Microsoft-Forbes data analysis competition (which we *won!*)

Predicting, whether a client is going to prolong the term of the contract or not


Metrics - AUC ROC 


Data:
  * Contracts
  * Attendence
  * Freezes
  * Communication

All the data tables were merged into one, after cleaning, transforming and feature engineering. 

Models:
- XGB
- Neaural Network
- Random forest
- Naive Bayes
- k-NN
- SVM

Models were tuned and optimized. Final prediction was made via ensebmling. Weighted average prediction method was used.

Final score on validation - 0.9846
