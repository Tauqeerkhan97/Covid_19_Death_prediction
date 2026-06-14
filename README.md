
  Covid-19 Death Prediction Using Machine Learning

This repository contains a Machine Learning project focused on predicting the mortality/death risk of Covid-19 patients based on their clinical data, symptoms, and demographic features. This tool can assist healthcare professionals in prioritizing high-risk patients and allocating critical medical resources effectively.

  Project Overview
During the global pandemic, early triage of high-risk patients became crucial. This project leverages historical patient datasets to build a classification model that predicts whether a Covid-19 patient is at high risk of death based on medical indicators (such as age, gender, pre-existing conditions, and initial symptoms).

  Tech Stack & Tools Used
Language: Python
Libraries: `Pandas` & `NumPy` (Data Manipulation & Preprocessing)
`Matplotlib` & `Seaborn` (Data Visualization & EDA)
`Scikit-Learn` (Model Training, Testing, and Evaluation)
* **Environment:** Jupyter Notebook / Google Colab

 Key Features of the Pipeline
1. **Data Cleaning:** Handling missing values, removing duplicates, and structuring inconsistent patient logs.
2. **Exploratory Data Analysis (EDA):** Visualizing correlation between age, pre-existing comorbidities (like diabetes, hypertension), and the survival rate.
3. **Feature Engineering:** Encoding categorical variables and scaling numerical attributes for optimal model performance.
4. **Model Implementation:** Training classification algorithms (such as Logistic Regression, Decision Trees, or Random Forest) to predict the outcome.
5. **Evaluation:** Checking model viability using Accuracy, Confusion Matrix, Precision, Recall, and F1-Score.

  Repository Structure

├── Data/                             # Raw or processed dataset files
├── Covid_19_Death_prediction.ipynb   # Main Jupyter notebook containing implementation
├── README.md                         # Project documentation
└── requirements.txt                  # Dependencies list (if applicable)


 How to Run Locally
1. Clone the repository:
Bash
git clone [https://github.com/Tauqeerkhan97/Covid_19_Death_prediction.git](https://github.com/Tauqeerkhan97/Covid_19_Death_prediction.git)
cd Covid_19_Death_prediction
2. Install Dependencies:
Bash
pip install pandas numpy scikit-learn matplotlib seaborn
3. Run the Notebook:
Launch Jupyter Notebook or open the file in Google Colab to run the cells sequentially:

Bash
jupyter notebook Covid_19_Death_prediction.ipynb
 Future Scope
Implementing Deep Learning models (Neural Networks) for higher precision.

Deploying the model as a web application using Flask or Streamlit.

Integrating real-time medical datasets from global health organizations.
