I am a data scientist and a statistician. I am passionate about getting to the core of problems that matter and solving them efficiently. Sometimes, the efficient way involves using data which is where I come in as a data scientist. Data can be used for inspiration (**Analyst** for e.g. visual dashboards, insights, trends etc.), or to make few high stakes decisions (**Statistician** for e.g. which product to launch, which ads to air etc.) or to automate multiple decisions (**Machine learning modeller** for e.g. recommendation, fraud detection etc.). The tools used by analysts, statisticians and machine learning modellers are often the same. The difference is in what they are used for and how they are used. <br>

Reach out to me on [LinkedIn](https://www.linkedin.com/in/mishahmehta/) or email me at mehtamishah@gmail.com <br>

Here are some of the projects I have worked on over the last year.

# Machine Learning
## Project Breast Cancer Detection
Built a classifier model to detect breast cancer. <br><br>

Choosing a metric: It is important to set the metric of success before you actually implement the algorithm so you don't cheat. Since I was using an imbalanced dataset, instead of accuracy, I choose sensitivity as the model metric. It is also important to know what is the score on the sensitivity metric previously, without using machine learning algorithms so the metric can tell us whether the machine model is indeed better than humans in doing the job. <br> <br>

Built multiple models, namely logistic regression classifier, k-Nearest Neigbors (k-NN) classifier, support vector machine (SVM) classifier, kernel SVM classifier, Naive Bayes classifier, Decision Tree classifier, and Random Forest classifier. Code for all algoriths can be found [here](https://github.com/mehtamishah/Breast-Cancer-Detection). <br> <br>

Best performance was achieved on a k - Nearest neighbors classifier model. On the test set, achieved <br>
Sensitivity = 0.95 # The ability to determine the patient cases (malignant tumors) correctly <br>
Specificity = 0.98 # The ability to determine the healthy cases (benign tumors) correctly <br>
roc_auc_score = 0.97

## Project Predicting net electrical energy output in a combined cycle power plant
Built a model to increase efficiency and costs in a power plant — by predicting net hourly electric energy output. <br> <br>

Assumptions: In a real word scenario, these assumptions would be backed by evidence by research or precedence.

Built multiple models, namely multiple linear regression, polynomial regression, support vector regression (SVR), decision tree regression, random forest regression and XGBoost regression. Code for all algoriths can be found [here](https://github.com/mehtamishah/Combined-Cycle-Power-Plant). <br> <br>

Best performance was achieved on a random forest regressor model. <br>
Achieved prediction accuracy of R2 score = 0.96, Mean absolute error = 2.44 on the test set

## Project Finding clusters to help the mall business look for growth opportunities
Built a model to identify clusters in mall-going customers. <br><br>

Used both Hierarchical and K-Means Clustering algorithms. Code for both algoriths can be found [here](https://github.com/mehtamishah/Finding-Clusters-in-Mall-Customers). <br><br>

Through clustering algorithms was able to find 5 clusters. Deduced a high income, high spending score cluster of customers that the mall can reach out to in future marketing campaigns.
