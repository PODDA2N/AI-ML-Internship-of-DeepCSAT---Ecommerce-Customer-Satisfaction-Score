# AI-ML-Internship-of-DeepCSAT---Ecommerce-Customer-Satisfaction-Score

Project Overview:

This project was completed as part of my Python/AI-ML Internship, focusing on analyzing customer support interactions in an eCommerce environment. The goal of the project is to understand the key factors influencing Customer Satisfaction (CSAT Score) and to build predictive models that estimate customer satisfaction based on operational, transactional, and textual data.
The dataset contains customer service interaction details such as communication channel, issue category, product information, order details, agent handling time, and textual customer feedback. Through data analysis, visualization, and machine learning techniques, the project aims to uncover meaningful insights that can help improve customer service performance and overall customer experience.

Dataset Description:

The dataset contains customer support interaction records with the following key variables:
•	Unique id – Unique identifier for each interaction record
•	channel_name – Channel through which the customer contacted support
•	category / Sub-category – Type of issue reported by the customer
•	Customer Remarks – Text feedback provided by the customer
•	Order_id – Unique identifier of the order
•	order_date_time – Date and time when the order was placed
•	Issue_reported at – Timestamp when the issue was reported
•	issue_responded – Timestamp when the support agent responded
•	Survey_response_Date – Date when the customer submitted the satisfaction survey
•	Customer_City – City of the customer
•	Product_category – Category of the purchased product
•	Item_price – Price of the product
•	connected_handling_time – Time spent by the agent resolving the issue
•	Agent_name / Supervisor / Manager – Customer support hierarchy information
•	Tenure Bucket – Experience level of the support agent
•	Agent Shift – Shift in which the issue was handled
•	CSAT Score – Customer satisfaction rating given after issue resolution

Project Workflow:

1. Understanding Variables
•	Reviewed dataset structure and variable types
•	Identified categorical, numerical, textual, and datetime variables
•	Interpreted business meaning of each feature

2. Data Wrangling
•	Cleaned column names and corrected data formats
•	Converted datetime columns into proper datetime format
•	Created derived features such as response time and interaction duration

3. Handling Missing Values
•	Identified missing values in different columns
•	Applied appropriate techniques such as:
o	Filling missing text fields
o	Mode/median replacement for categorical and numerical features

4. Exploratory Data Analysis (EDA)
Performed extensive EDA to understand data distribution and patterns using:
•	Histograms
•	Box plots
•	Scatter plots
•	Pie charts
•	Correlation heatmaps
•	Pair plots
This helped identify relationships between handling time, product category, communication channel, and CSAT score.

6. Data Visualization & Storytelling
Used visualization techniques to communicate insights such as:
•	Customer interaction distribution across channels
•	Impact of handling time on customer satisfaction
•	Product categories with higher complaint rates
•	Agent performance patterns
These visual insights help in understanding operational inefficiencies.

7. Hypothesis Testing
Statistical hypothesis testing was performed to examine relationships between key variables and customer satisfaction.
Examples include:
•	Testing whether handling time significantly affects CSAT Score
•	Examining whether communication channels impact customer satisfaction

8. NLP Feature Engineering
The Customer Remarks column was processed using Natural Language Processing techniques:
•	Text cleaning and preprocessing
•	Lowercasing and punctuation removal
•	Stopword removal
•	Tokenization
•	Text normalization
•	Text vectorization for machine learning models
This allowed extraction of meaningful insights from textual feedback.

9. Machine Learning Model Implementation
Machine learning models were implemented to predict Customer Satisfaction Score (CSAT Score).
Regression Task
A regression model was trained to predict the numerical CSAT score using relevant features from the dataset.

Model Evaluation
Regression Model Evaluation
Regression models were evaluated using the following metrics:
•	R² Score
•	Mean Squared Error (MSE)
•	Root Mean Squared Error (RMSE)
These metrics measure how well the model predicts the actual CSAT score.

Classification Model Evaluation
For classification tasks, model performance was evaluated using:
•	Accuracy
•	Precision
•	Recall
•	F1 Score
These metrics assess how well the model classifies customer satisfaction levels.

Cross Validation
To ensure model robustness and prevent overfitting, Cross Validation techniques were applied during model training.
This helps evaluate model performance on multiple data splits and ensures better generalization.

Hyperparameter Tuning
Hyperparameter optimization was performed using GridSearchCV to identify the best combination of parameters for improving model performance.
This step helps enhance model accuracy and predictive capability.

Artificial Neural Network (ANN) Model
An Artificial Neural Network (ANN) was also implemented to capture complex relationships within the dataset.
Steps involved:
1.	Feature scaling and pre processing
2.	Designing neural network architecture
3.	Compiling the model with appropriate loss function and optimizer
4.	Training the model on the dataset
5.	Evaluating model performance
6.	Generating predictions on test data
The ANN model helps improve predictive performance by learning nonlinear relationships between features and customer satisfaction.

Key Insights
Some key findings from the analysis include:
•	Longer handling time tends to negatively impact customer satisfaction
•	Certain product categories generate more customer issues
•	Communication channel influences customer experience
•	Agent experience and shift timing may affect resolution efficiency

Technologies Used
•	Python
•	Pandas
•	NumPy
•	Matplotlib
•	Seaborn
•	Scikit-learn
•	TensorFlow / Keras
•	Natural Language Processing (NLP)

Project Outcome
This project demonstrates the use of data analysis, visualization, NLP, and machine learning techniques to analyze customer service interactions and predict customer satisfaction in an eCommerce environment.
The insights generated can help organizations:
•	Improve customer support processes
•	Optimize agent performance
•	Reduce issue resolution time
•	Enhance overall customer experience.
