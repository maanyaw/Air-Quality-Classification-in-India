
🌫️ Air Quality Classification in India
This project analyzes and classifies air quality levels in various regions of India using machine learning techniques. It includes preprocessing of environmental data, visual analytics, and classification using Decision Tree and Random Forest algorithms to categorize air quality based on US EPA standards.

📌 Project Highlights
🇮🇳 Geographic Focus: India

📊 Data Source: IndianWeatherRepository.csv

🧹 Preprocessing:

Handling missing values

Removing duplicates

Outlier removal using IQR

Min-Max normalization

📈 Visualization:

Box plots before and after outlier removal

Histograms of pollutants

Correlation heatmap

AQI category distribution

🧠 Models Used:

Decision Tree Classifier

Random Forest Classifier

GridSearchCV for hyperparameter tuning

📦 Categorization: Air quality classified into:

Good

Moderate

Unhealthy for Sensitive Groups

Unhealthy

Hazardous

🔍 Prediction Support: Accepts new pollutant data and classifies air quality based on trained models.

📁 Files
air_quality_classification_in_india_.py – Main code file with complete pipeline

IndianWeatherRepository.csv – Dataset containing air quality metrics across Indian regions

📌 Requirements
Make sure to install the following Python libraries:

pip install pandas scikit-learn seaborn matplotlib plotly

🚀 Running the Project
Clone the repository and place the CSV file in the working directory.

Run the Python script air_quality_classification_in_india_.py in a Jupyter Notebook or Google Colab.

Visualizations will pop up using plotly and matplotlib.

Train and test accuracies along with classification reports and confusion matrices will be shown.

You can also pass custom input data to the model for prediction.

📍 Scope
This project is intended for analyzing and classifying air quality data within India only, based on pollutant levels and corresponding health indexes.

