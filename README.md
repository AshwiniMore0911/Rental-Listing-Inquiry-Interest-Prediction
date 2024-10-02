# Rental-Listing-Inquiry-Interest-Prediction
Developing a predictive model to classify rental listings based on inquiry interest levels (low, medium, high) using a Multi-Class One-vs-All Gradient Boosting classifier. The project leverages TF-IDF features and employs Grid Search for hyperparameter tuning to enhance model performance.

**Project Overview**
In a competitive real estate market, understanding the level of interest potential renters have in listings is crucial for landlords and property managers. This project focuses on predicting rental inquiry interest levels (low, medium, high) using a Multi-Class One-vs-All Gradient Boosting classifier. By leveraging advanced machine learning techniques and feature extraction methods, we aim to provide actionable insights that can enhance marketing strategies and improve tenant engagement.

**Objectives**
Interest Level Prediction: Develop a predictive model to classify rental listings based on the level of inquiry interest.
Feature Engineering: Utilize TF-IDF and other feature selection techniques to optimize model inputs for better performance.
Hyperparameter Tuning: Implement Grid Search to fine-tune model parameters, maximizing accuracy and efficiency.

**Technologies Used**
Programming Language: Python
Machine Learning Framework: Scikit-learn, XGBoost
Feature Engineering: TF-IDF, NLTK, Pandas
Modeling Techniques: Gradient Boosting, One-vs-All Classification
Hyperparameter Tuning: Grid Search

**Data Overview**
The project utilizes a dataset from RentHop, which includes:

Rental listing details (location, price, amenities)
Inquiry data (number of inquiries, inquiry timestamps)
Descriptive text for each listing
This dataset provides a rich source of information for predicting renter interest levels.

**Methodology**
1. Data Collection and Preprocessing
Data Acquisition: Gather rental listing data from RentHop or similar platforms.
Data Cleaning: Process the dataset to handle missing values and outliers, ensuring data quality.

2. Feature Engineering
TF-IDF Vectorization: Convert textual descriptions of listings into numerical features using TF-IDF to capture the importance of words in the context of rental interest.
Ablation for Feature Selection: Identify and retain the most relevant features through ablation studies, enhancing model performance.

3. Model Development
One-vs-All Gradient Boosting Classifier:
Train a Multi-Class classifier that predicts the interest level (low, medium, high) based on the extracted features.
Implement Gradient Boosting to improve predictive accuracy by combining multiple weak learners.

4. Hyperparameter Tuning
Grid Search: Utilize Grid Search to systematically explore various combinations of hyperparameters, ensuring optimal model performance.

5. Evaluation and Results
Model Evaluation: Assess the model’s performance using metrics such as accuracy, precision, recall, and F1-score to determine its effectiveness in classifying rental inquiry interest.
Insights Generated: Analyze the results to derive insights on what factors contribute most to interest levels, guiding landlords in their marketing efforts.

**Key Insights**
Predictive Accuracy: The model successfully classifies rental listings by inquiry interest levels, providing landlords and property managers with valuable insights into renter behavior.
Feature Importance: Analysis reveals which features significantly influence interest levels, helping optimize listing descriptions and marketing strategies.

**Future Work**
Integrate More Data Sources: Expand the dataset to include additional variables such as user demographics and external market conditions for improved predictions.
Real-Time Prediction Dashboard: Develop an interactive dashboard to provide real-time predictions of inquiry interest for new listings as they are added.
Advanced Modeling Techniques: Explore deep learning approaches to enhance the model’s predictive capabilities further.

**Conclusion**
This project highlights the power of machine learning in predicting rental inquiry interest levels, offering valuable insights for stakeholders in the real estate market. By applying advanced techniques in feature engineering and modeling, we can improve marketing strategies and enhance tenant engagement.

Get Involved
If you have questions, suggestions, or would like to collaborate on this project, please feel free to reach out!
