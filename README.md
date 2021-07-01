I am a data scientist and a statistician. I am passionate about getting to the core of problems that matter and solving them efficiently. Sometimes, the efficient way involves using data which is where I come in as a data scientist. Data can be used for inspiration (**Analyst** for e.g. finding insights or trends), or to make a few high stakes decisions (**Statistician** for e.g. deciding which product to launch or which ads to air) or to automate multiple decisions (**Machine learning modeler** for e.g. making recommendations or detecting fraud). The tools used by analysts, statisticians and machine learning modelers are often the same. The difference is in what they are used for and how they are used. <br>

You can find me on [LinkedIn](https://www.linkedin.com/in/mishahmehta/) or email me at mehtamishah@gmail.com <br>. You can check out my work on Tableau [here](https://public.tableau.com/profile/misha.h.mehta#!/).

Here are some of the projects I have worked on over the last year.

# Machine Learning
## Project Breast Cancer Detection
Built a classifier model to detect breast cancer. <br>

Choosing a metric: It is important to set the metric of success before you actually implement the algorithm so you don't cheat. Since I was using an imbalanced dataset, instead of accuracy, I choose sensitivity as the model metric. It is also important to know what is the score on the sensitivity metric previously, without using any machine learning algorithms so the metric can tell us whether the machine learning model is indeed better than humans to do the job. <br>

Built multiple models, namely logistic regression classifier, k-Nearest Neigbors (k-NN) classifier, support vector machine (SVM) classifier, kernel SVM classifier, Naive Bayes classifier, Decision Tree classifier, and Random Forest classifier. Code for all these algorithms can be found [here](https://github.com/mehtamishah/Breast-Cancer-Detection). <br>

Best performance was achieved on a k - Nearest neighbors classifier model. On the test set, achieved <br>
Sensitivity = 0.95  #The ability to determine the patient cases (malignant tumors) correctly <br>
Specificity = 0.98  #The ability to determine the healthy cases (benign tumors) correctly <br>
roc_auc_score = 0.97 <br>

## Project Predicting net electrical energy output in a combined cycle power plant
Built a model to increase efficiency and costs in a power plant — by predicting net hourly electric energy output. <br>

Assumption: Improvement in prediction of electric energy output is linked to a desirable output such as energy savings, minimizing costs or maximizing revenue. In a real word scenario, assumptions would be backed by evidence, either research or precedence. <br>

Built multiple models, namely multiple linear regression, polynomial regression, support vector regression (SVR), decision tree regression, random forest regression and XGBoost regression. Code for all these algorithms can be found [here](https://github.com/mehtamishah/Combined-Cycle-Power-Plant). <br>

Best performance was achieved on a random forest regressor model. <br>
Achieved prediction accuracy of R2 score = 0.96, Mean absolute error = 2.44 on the test set <br>

## Project Identifying growth opportunities for the mall business
Built a model to identify clusters in mall-going customers. <br>

Used both Hierarchical and K-Means Clustering algorithms. Code for both algorithms can be found [here](https://github.com/mehtamishah/Finding-Clusters-in-Mall-Customers). <br>

For the K-Means clustering used the elbow method to identify the optimum number of clusters and for hierarchical clustering used the dendogram to identify the optimum number of clusters.

Clustering revealed 5 clusters. 
1. Low income, low spending score
2. Low income, high spending score
3. Medium income, medium spending score
4. High income, low spending score
5. High income, high spending score

Future marketing strategies and campaigns can be customized to meet the needs of the high income, high spending score cluster of customers.
