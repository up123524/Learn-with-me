# Learn-with-me

**Some of the explanations I write for myself as I learn concepts **

*My experiences:* 
The pareto principle applies in that 80% of the usefulness of a project is in 20% of the work. This is especially true of Data engineering where the marginal gains of creating an ever improving model pale in comparison to the gain made through proper evaluation, collection, cleaning and exploration of data. Despite python being somewhat dominant my personal taste for EDA (Exploratory Data Analysis) tends towards R as a software built by statisticians (Hadley Wickham is one of my personal heroes.) These incredibly powerful and easy to implement packages can represent that 20% of the work!!

Evaluate the use case of the model careful, statistical intution is a valuable skill and being able to accurately assess the validility of your approach before you start in regards to certain aspects e.g is it more valuable to minimise Type 1 or Type 2 error in my predictions is a multiplier in you workflow. 

True Positive Rate( Sensitivity or Recall): TPR=TP/TP+FN is a ratio identifying what percentage of Positive hits a model generates are accurate. 
A high TPR is beneficial. 

Type 1 Error: A type 1 error occurs when the null hypothesis is incorrectly rejected leading to a loss e.g. a placebo effect incorrectly identifies a new
medication as effective. It is particularly important when the cost of a positive outcome is high e.g. necessary medical treatment. T1 Error is related 

False positive Rate: FPR = FP/TP+TN. 

Type 2 Error: A type 2 error occurs when a model fails to indentify cases where we should reject the null hypothesis relating it to False Negatives. This indicated a deficiency in the models ability correctly identify positive cases. To borrow from medicine again, this is akin to a XRay scanner that misses the positive sign of cancer. In this instance the 'low probability' is the prospect of a patient having cancer so we set up H0: There is no incident of Cancer, H1: the patient has cancer. In this case the model needs to err on the side of caution. 

ROC AUC (Receiver Operating Characteristic - Area Under the Curve): This is a method for evaluating the performance of a binary classification model. Balances the True Positive Rate and False Positive Rate 
probabilities to create a measure that is generally more appropriate for highly imbalanced data-sets. The balance of TPR and FPR into one metric can provide a more balanced view of the characteristics of a dataset.

*Sampling methods for biased datasets*
SMOTE:

V-fold cross validation: 




