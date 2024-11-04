
# 🏥 Multiple Disease Prediction: Heart Disease, Diabetes, and Parkinson's Disease

## 📖 Overview

This project utilizes advanced machine learning techniques to predict the likelihood of three significant health conditions: **heart disease**, **diabetes**, and **Parkinson's disease**. By providing an intuitive interface built with **Streamlit**, this tool enables users to input health metrics and receive predictions that can assist in early diagnosis and preventive healthcare.

## 🎯 Objectives

- **Data Collection**: Use comprehensive datasets containing various patient health metrics linked to heart disease, diabetes, and Parkinson's disease.
- **Data Preprocessing**: Clean and prepare the data by handling missing values and normalizing the features to enhance model accuracy.
- **Model Development**: Implement and compare different machine learning models for each disease:
  - Heart Disease Prediction
  - Diabetes Prediction
  - Parkinson's Disease Prediction
- **User Interface**: Develop an interactive Streamlit application to allow users to input their health data and receive accurate predictions.

## 📊 Datasets

The datasets used for this project are sourced from various reputable repositories, ensuring a diverse range of patient data. Below are some of the details of the datasets utilized:

### 1. Heart Disease Dataset
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)
- **Key Features**:
  | Feature               | Description                                   |
  |-----------------------|-----------------------------------------------|
  | **Age**               | Age of the individual                         |
  | **Gender**            | Gender of the individual                      |
  | **Blood Pressure**    | Systolic blood pressure                       |
  | **Cholesterol**       | Serum cholesterol in mg/dl                   |
  | **Max Heart Rate**    | Maximum heart rate achieved                   |
  | **Heart Disease Status** | Target variable indicating heart disease   |

### 2. Diabetes Dataset
- **Source**: [Kaggle Diabetes Dataset](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
- **Key Features**:
  | Feature               | Description                                   |
  |-----------------------|-----------------------------------------------|
  | **Pregnancies**       | Number of times pregnant                      |
  | **Glucose**           | Plasma glucose concentration                   |
  | **BMI**               | Body Mass Index                               |
  | **Insulin**           | Insulin level                                 |
  | **Diabetes Status**   | Target variable indicating diabetes            |

### 3. Parkinson's Disease Dataset
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Parkinsons)
- **Key Features**:
  | Feature               | Description                                   |
  |-----------------------|-----------------------------------------------|
  | **Age**               | Age of the individual                         |
  | **Gender**            | Gender of the individual                      |
  | **Jitter**            | Variability in frequency                       |
  | **Shimmer**           | Variability in amplitude                       |
  | **Parkinson's Status**| Target variable indicating Parkinson's disease |


## 🛠️ Installation

To set up the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/multiple-disease-prediction.git
   cd multiple-disease-prediction
   ```

2. **Install the required packages**:
   Ensure you have Python installed (preferably Python 3.7 or later). Then, install the necessary libraries:
   ```bash
   pip install -r requirements.txt
   ```

## 🚀 Usage

### Training the Models

To train the disease prediction models, run the following command in your terminal:
```bash
python train_models.py
```
This script will preprocess the data, train the models, and save the trained models for future use.

### Running the Streamlit Application

To launch the interactive user interface, execute:
```bash
streamlit run app.py
```
This command will start the Streamlit server and open the application in your web browser.

### User Interface Features

Once the Streamlit application is running, users will be presented with:
- **Input Fields**: Enter your health metrics for each disease (age, gender, medical history, etc.).
- **Predict Button**: Click to receive predictions for heart disease, diabetes, and Parkinson's disease.
- **Output Display**: View the prediction results and confidence scores.


## 📈 Results

The performance of the disease prediction models is evaluated and summarized in the `results/` directory. Key outputs include:

- **Model Accuracy**:
  - Heart Disease Model: 88%
  - Diabetes Model: 90%
  - Parkinson's Disease Model: 85%




## 🔮 Future Work

Future enhancements may include:
- **Data Expansion**: Incorporating more diverse datasets for improved model training.
- **Feature Engineering**: Adding additional features that may enhance prediction accuracy.
- **Enhanced User Experience**: Improving the Streamlit app with more visualizations and user feedback options.

## 🙏 Acknowledgments

- **Libraries Used**: [Pandas](https://pandas.pydata.org/), [Scikit-learn](https://scikit-learn.org/), [Streamlit](https://streamlit.io/), [Matplotlib](https://matplotlib.org/)
