
# Customer Churn in the Telecom Industry:

Customer churn refers to the scenario where customers or subscribers cease their association with a company or service provider.

In the dynamic telecom sector, customers have the flexibility to select from a range of service providers, often transitioning between them. With an annual churn rate of 15-25 percent, the telecommunications industry faces intense competition.

Tailoring individualized customer retention strategies poses a challenge due to the sheer volume of customers most firms cater to. Allocating substantial resources to each customer is impractical, given the associated costs that may outweigh the incremental revenue. However, by accurately predicting which customers are at risk of leaving, companies can concentrate their retention efforts on these "high-risk" clients. The ultimate objective is to expand market reach and enhance customer loyalty. The crux of success in this competitive landscape hinges on understanding and retaining the customer base.

Customer churn stands out as a pivotal metric since retaining existing customers proves more cost-effective than acquiring new ones.

To proactively identify potential churn indicators, it is imperative to develop a comprehensive understanding of customers and their interactions across various touchpoints. By addressing churn effectively, businesses can not only safeguard their market standing but also foster growth and prosperity. As the network expands, the initial acquisition costs decrease, leading to higher profits. Therefore, the primary focus for organizational success lies in reducing client attrition and executing robust retention strategies.

Objectives:
1. Determine the percentage of churned customers and those maintaining active services.
2. Analyze data to identify key features influencing customer churn.
3. Identify the most suitable machine learning model for accurate classification of churn and non-churn customers.

Approach:
1. Our methodology involved conducting data preprocessing, analyzing missing values, engaging in feature engineering, identifying high-value customers, tagging churners, and conducting essential exploratory data analysis (EDA). We have highlighted notable insights gleaned from the EDA process.
2. In the realm of data preparation, we segmented the data into training and testing sets, leveraging SMOTE on the training set to address class imbalance effectively.
3. We conducted an in-depth analysis of multiple models to identify the optimal one for predicting high accuracy, precision, and recall, while also extracting and evaluating the feature importance in relation to churn prediction.

Model 	Accuracy 	Precision 	Recall 	AUC-Score 	F1_score
0 	Logistic Regression 	0.683333 	0.674658 	0.697345 	0.683455 	0.685814
1 	Decision Tree 	0.852632 	0.841652 	0.865487 	0.852743 	0.853403
2 	Random Forest 	0.937719 	0.959108 	0.913274 	0.937507 	0.935630
3 	Gradient Boosting 	0.847368 	0.894949 	0.784071 	0.846818 	0.835849
4 	Support Vector 	0.670175 	0.809836 	0.437168 	0.668149 	0.567816
5 	Ada Boost 	0.771930 	0.774775 	0.761062 	0.771835 	0.767857
6 	KNeighbors Classifier 	0.831579 	0.763047 	0.957522 	0.832674 	0.849294

