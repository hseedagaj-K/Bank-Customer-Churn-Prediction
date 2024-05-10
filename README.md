# Bank-Customer-Churn-Prediction :
To analyze bank customer churn behavior, identify key attrition factors, and develop predictive models to forecast churn probabilities, aiding proactive customer retention strategies using advanced data analysis and machine learning techniques.

- **Abstract :**

    Now a -days there are a lot of service providers available in every business. There is no shortage of customers in any options. Mainly, in the banking sector when people want to keep their money safely they have a lot of options. As a result, customer churn and loyalty of customers have become a major problem for most banks. In this paper, a method that predicts customer churn in banking using Machine learning with ANN. This research promotes the exploration of the likelihood of churning by customer loyalty. The logistic regression,random forest,decision tree algorithms are used in this study.This study is done on a dataset called churn_data. The dataset was collected from Kaggle. The results are compared to find an appropriate model with higher accuracy. As a result, the Random Forest algorithm achieved higher accuracy than other algorithms. And accuracy was nearly 87%. The least accuracy was achieved by the Decision tree algorithm and it was 78.59% accuracy.Customer churn and engagement have become one of the top issues for most banks. In this project, a method to predict the customer churn in a Bank, using machine learning techniques, which is a branch of artificial intelligence, is proposed. The research promotes the exploration 5 of the likelihood of churn by analyzing customer behavior.
  
- **Introduction :**

    Churning means a customer who leaves one company and transfers to another company. It is not only a loss in income but also other negative effects on the operations and also mainly Customer Relation Management is very important for banking.. It notes that the current generation's advanced knowledge and diverse demands pose challenges for service providers to innovate and meet customer expectations effectively.

   Machine learning, a subset of artificial intelligence, enables computers to learn from data without explicit programming. It involves specialized algorithms that process training data to make predictions on new data. Machine learning can be categorized into supervised, unsupervised, and reinforcement learning. Supervised learning involves labeled data, unsupervised learning clusters unlabeled data, and reinforcement learning improves based on feedback from the environment.

  Data scientists use various machine learning algorithms to discover patterns for actionable insights. These algorithms fall into two groups: supervised and unsupervised learning. Supervised learning, which dominates practical machine learning, involves mapping input variables to output variables using algorithms like logistic regression, decision trees, etc. The data used for supervised learning must be labeled with correct answers, typically categorized into classification problems where the goal is to predict categorical outcomes from input variables.

  ![g](https://github.com/hseedagaj-K/Bank-Customer-Churn-Prediction/assets/139363976/037ce759-37b4-4ac5-9b0d-23693cbb94b4)

- **Methodology :**

    This section explains the various works that have been done in order to predict the customer churn. It includes machine learning models.Binary Classification model is used for predicting the customer churn.Though a good improvement is noticed with this model, the data that has been used in this is not commonly available at all times. Churn prediction is a binary classification problem.It has  been observed that the accuracy of the classifiers differs for different zones of the dataset.

    **Exploration data analysis of variable identification**
  
    ● Loading the given dataset
  
    ● Import required libraries packages
  
    ● Analyze the general properties
  
    ● Find duplicate and missing values
  
    ● Checking unique and count values
  
   **Exploratory data analysis of bi-variate and multivariate**
  
    ● Plot diagram of pairplot, heatmap, bar chart and Histogram

    ![Churn_Distribution](https://github.com/hseedagaj-K/Bank-Customer-Churn-Prediction/assets/139363976/04b0fcfe-79ff-4ef1-80c4-e1459998f79a)

  **Exploatory Data Analysis :**

    Data visualization is an important skill in applied statistics and machine learning. Statistics does indeed focus on quantitative descriptions and estimations of data. Data visualization provides an important suite of tools for gaining a qualitative understanding.This can be helpful when exploring and getting to know a dataset and can help with identifying patterns, corrupt data, outliers, and much more. With a little domain knowledge, data visualizations can be used to express and demonstrate key relationships in plots and charts that are more visceral and stakeholders than measures of association or significance. Data visualization and exploratory data analysis are whole fields themselves and it will recommend a deeper dive into some the books mentioned at the end.

  ![Gender_Churn](https://github.com/hseedagaj-K/Bank-Customer-Churn-Prediction/assets/139363976/26fdc46a-36b2-4d39-9c64-a56b11a4e09f)

- **Dataset Description :**

   To build the bank customer churn prediction model we have used a bank loan dataset. The data file churn_modeling.csv contains the information used to create the model. It consists of 10000 rows and 14 columns. The columns represent the variables, while the rows represent the instances.This Dataset is composed of 4 concepts they are Data source,variables,Instances,Missing values.This dataset uses the following 14 variables:*Row Number*, *CustomerId*, *Surname*, *CredirScore*, *Geography*, *Gender*, *Age*, *Tenure*, *Balance*, *NumofProducts*, *HasCrCard*, *IsActiveMember*, *EstimatedSalary*, *Exited/Not exited*.


- **ALgorithm :**

   In this paper we have used three algorithms and compared among them.They are Random Forest,Decision tree,Logistic Regression.

  - **Logistic Regression :**
    It is a statistical method for analysing a data set in which there are one or more independent variables that determine an outcome. The outcome is measured with a dichotomous variable (in which there are only two possible outcomes). The goal of logistic regression is to find the best fitting model to describe the relationship between the dichotomous characteristic of interest (dependent variable = response or outcome variable) and a set of independent (predictor or explanatory) variables. Logistic regression is a Machine Learning classification algorithm that is used to predict the probability of a categorical dependent variable. In logistic regression, the dependent variable is a binary variable that contains data coded as 1 or 0.

  - **Random Forest :**

     Random Forest is a versatile and powerful machine learning algorithm widely used for both classification and regression tasks. It operates by constructing multiple decision trees during training and outputting the mode of the classes (classification) or the mean prediction (regression) of the individual trees. The key characteristic of Random Forest is its ability to introduce randomness in the tree-building process by considering a random subset of features and data samples at each split. This randomness helps to reduce overfitting and improves the model's generalization performance. Random Forest is known for its robustness, scalability, and capability to handle high-dimensional datasets with complex relationships.

  ![image](https://github.com/hseedagaj-K/Bank-Customer-Churn-Prediction/assets/139363976/bea008a6-9f2b-425b-a0b1-a3730d26b36f)

  ![Confusion_Matrix](https://github.com/hseedagaj-K/Bank-Customer-Churn-Prediction/assets/139363976/d510ccce-6ef7-4c9a-acd2-fdf0f503200d)


- **Conclusion :**

    The study, aimed at predicting customer churn in the banking sector using machine learning techniques, provides several important findings and implications for both academic research and industry practices. Firstly, the results show that machine learning methods, specifically the Random Forest model, can effectively predict customer churn. Compared to the Logistic Regression model, the Random Forest model delivered superior performance across all metrics. This underlines the significant potential of advanced machine learning techniques in tackling customer retention challenges in the banking sector. Secondly, our research offers insights into the factors influencing customer churn. Specifically, customer age was found to be the most significant variable impacting churn. This indicates that age-specific interventions could be an effective part of churn prevention strategies in banking institutions. In conclusion, this study represents a step forward in understanding customer churn in the banking sector through machine learning. The knowledge generated from this research can contribute to enhancing customer relationship management strategies, improving customer retention, and ultimately driving sustained growth in the banking industry.Despite these contributions, our study is not without limitations. The findings are based on a single dataset, which may not fully capture the diversity and complexity of the global banking customer base. 
    
