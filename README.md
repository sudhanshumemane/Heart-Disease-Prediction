# Introduction:

**Objective:** To determine the probability of heart failure by using Naive Bayes classifier 

The prevention of Heart diseases has become more than necessary. Good data-driven systems for predicting heart diseases can improve the entire research and prevention process, making sure that more people can live healthy lives. This is where Machine Learning comes into play. Machine Learning helps in predicting the Heart diseases, and the predictions made are quite accurate.
We've used Gaussian NB algorithm of Naive Bayes classifier family to achieve higher accuracy rate, implemented in Python, to predict the presence of heart disease in a patient. This is a classification problem, with input features contains 13 of parameters, and the target variable as a binary variable, predicting the probability of person's chances of heart failure.

**Research Paper:** https://ijarcce.com/wp-content/uploads/2022/05/IJARCCE.2022.11455.pdf

**Dataset:** https://archive.ics.uci.edu/ml/datasets/heart+disease

**Technologies Used:** Python, Jupyter Notebook, Flask, JavaScript, HTML, CSS

**Libraries Used:** 
1. Numpy (for mathematical operations on arrays)
2. Pandas (for data analysis)
3. Matplolib (for data visualization)
4. Seaborn (for data visualization)
5. Sci-kit Learn (for data modelling) 

**Parameters Used:**

| **#**  |  **Attributes** |   **Description**    |
| :--:| :--------: | :--------------------- | 
| 1  |   Age     |    Age in years |
| 2  |  Sex      | Male: 1, Female: 0  |
| 3  |  cp       | Chest pain type: 1: typical angina, 2: atypical angina, 3: non-anginal pain, 4: asymptomatic | 
| 4  |  trestbps | Resting blood pressure  |
| 5  |  chol     | Serum cholestoral in mg/dl |
| 6  |  fbs      | Fasting blood sugar > 120 mg/dl |
| 7  |  restecg  | Resting electrocardiographic results (values 0,1,2) |
| 8  |  thalach  | Maximum heart rate achieved |
| 9  |  exang    | Exercise induced angina |
| 10 |  oldpeak  | Oldpeak = ST depression induced by exercise relative to rest |
| 11 |  slope    | The slope of the peak exercise ST segment |
| 12 |  ca       | No. of major vessels (0-3) colored by flourosopy |
| 13 |  thal     | thal: 3 = normal; 6 = fixed defect; 7 = reversable defect |


**Comparison between classifier models**

| **Predictive Model** | **Accuracy (%)** | **Time (sec)**  |
| Naive Bayes          | 85.25            | 1.8             |
| SVM                  | 91.97            | 2.9             |
| Logistic Regression  | 85.25            | 2.3             |

**Conclusion:**

The proposed system scalable, reliable and an expandable. The proposed working model can also help in reducing treatment costs by providing initial
diagnostics in time. The performance of the health’s diagnosis can be improved significantly by handling numerous class labels in the prediction process. 

**Future Improvements:**

Furthermore, we know that irrelevant features also degrade the performance of the prediction system and increased computation time. 
Thus, another innovative solution of our study to used features selection algorithms to selects the appropriate features that improve the classification accuracy as well as reduce the processing time of the preditive system.
In the future, we will use other features selection algorithms, optimization methods to further increase the performance of a predictive system for HD diagnosis






