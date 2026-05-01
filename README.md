🍄 Mushroom Classification ML Project

📌 Project Overview

This project focuses on building a Machine Learning model to classify mushrooms as edible or poisonous based on their physical characteristics. The dataset includes various features such as cap shape, color, gill structure, stem properties, and habitat.

🎯 Objective

To develop an accurate classification model that can predict whether a mushroom is edible or poisonous based on its physical features.

📊 Dataset Features

The dataset contains 61,069 rows and 21 columns with both numerical and categorical features.
Main Features Include:
Cap: diameter, shape, surface, color
Gill: attachment, spacing, color
Stem: height, width, root, surface, color
Veil and Ring features
Spore print color
Habitat and season
Target Variable: class
e = Edible
p = Poisonous

🔍 Data Analysis (EDA)

Checked missing values and data types
Performed countplots, histograms, boxplots, heatmaps
Analyzed feature vs class relationships
Identified patterns for poisonous and edible mushrooms

🧹 Data Preprocessing

Handled missing values using median (numerical) and mode (categorical)
Removed duplicate records
Converted data types appropriately
Encoded categorical variables using OneHotEncoder
Scaled numerical features using StandardScaler

⚙️ Machine Learning Pipeline

Used ColumnTransformer for preprocessing
Applied RandomOverSampler to handle class imbalance
Built pipelines using sklearn and imblearn

🤖 Models Used

Logistic Regression
Decision Tree
Random Forest
Support Vector Machine (SVM)
AdaBoost
XGBoost

🔍 Model Optimization

Hyperparameter tuning using GridSearchCV
Cross-validation for better model performance

📈 Results

Random Forest and XGBoost also showed strong performance
Balanced data improved prediction quality

🛠️ Tools & Technologies

Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
XGBoost
Imbalanced-learn
Jupyter Notebook

📂 Project Structure

Mushroom-Classification/

│── Data.csv │── Mushroom_Analysis.ipynb │── Mushroom_ML.ipynb │── Mushroom_Project_Presentation.pptx │── README.md

🙌 Author

POOJA KAYAL

Data Analyst | Machine Learning Enthusiast | Python Developer
