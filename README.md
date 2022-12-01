# XGBoost

*XGBoost is an ensemble learning method. Sometimes, it may not be sufficient to rely upon the results of just one machine learning model. 
Ensemble learning offers a systematic solution to combine the predictive power of multiple learners. The resultant is a single model which gives the 
aggregated output from several models.

*The models that form the ensemble, also known as base learners, could be either from the same learning algorithm or different learning algorithms. 
Bagging and boosting are two widely used ensemble learners. Though these two techniques can be used with several statistical models, the most predominant 
usage has been with decision trees.

*Bagging
 - While decision trees are one of the most easily interpretable models, they exhibit highly variable behavior. Consider a single training dataset that we 
   randomly split into two parts. Now, let’s use each part to train a decision tree in order to obtain two models.

 - When we fit both these models, they would yield different results. Decision trees are said to be associated with high variance due to this behavior.
   Bagging or boosting aggregation helps to reduce the variance in any learner. Several decision trees which are generated in parallel, form the base learners 
   of bagging technique. Data sampled with replacement is fed to these learners for training. The final prediction is the averaged output from all the learners.
   
*Boosting
 - In boosting, the trees are built sequentially such that each subsequent tree aims to reduce the errors of the previous tree. Each tree learns from its 
   predecessors and updates the residual errors. Hence, the tree that grows next in the sequence will learn from an updated version of the residuals.
