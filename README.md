This project implements a Smart Diabetes Health Prediction System using Machine Learning to predict the likelihood of diabetes based on health and lifestyle indicators. The system applies data-driven techniques to assist in the early detection of diabetes risk, supporting preventive healthcare and informed medical decision-making.

The model is developed using Python and Scikit-learn, with the Random Forest algorithm used for classification. The project is based on the CDC 2015 Diabetes Health Indicators Dataset, containing approximately 250,000 real-world health records. The complete machine learning workflow includes data preprocessing, exploratory data analysis, model training, evaluation, and deployment through an interactive interface.

Key Features:

• Binary classification of diabetic vs. non-diabetic individuals
• Comprehensive data preprocessing including scaling, cleaning, and handling missing values
• Random Forest–based prediction model with feature importance analysis
• Model evaluation using accuracy, precision, recall, F1-score, and confusion matrix
• Interactive Gradio-based demo UI for real-time predictions
• Modular and reproducible implementation suitable for academic and healthcare applications

Technologies Used:

• Python
• Scikit-learn
• Pandas, NumPy
• Matplotlib, Seaborn
• Gradio
• SMOTE (Imbalanced-learn)

Dataset:

Source: Kaggle – CDC 2015 Diabetes Health Indicators Dataset

Records: ~250,000

Features: 21 health-related attributes including BMI, blood pressure, cholesterol level, smoking habits, physical activity, age, income, and general health indicators.

Target Variable: Diabetes_binary (0 = Non-diabetic, 1 = Diabetic)

Objective:

To design and evaluate a machine learning model capable of accurately predicting diabetes risk using health-related indicators, demonstrating the practical application of machine learning in healthcare analytics and early disease detection systems.
