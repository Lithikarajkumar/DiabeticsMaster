# Diabetes Checkup Application

This project is a machine learning-based web application developed using [Streamlit](https://streamlit.io/) to predict whether a person is diabetic based on their medical data. The app allows users to input personal health parameters and view visualizations comparing their data with others from the dataset.

## Features

- **User Inputs**: Users can input various health parameters such as glucose level, BMI, blood pressure, insulin level, etc., via sliders in the sidebar.
- **Visualizations**: Graphs are generated to compare the user's data against the overall dataset, showing relationships between age and medical conditions.
- **Prediction**: The app uses a Random Forest Classifier model to predict whether the user is diabetic or not.
- **Accuracy**: Displays the accuracy of the model on the training data.

## Dataset

The model is trained on the popular [Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database) which is available on Kaggle. This dataset consists of several diagnostic measurements including:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function (DPF)
- Age

## Installation

To run the application locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone <repository-url>

2. **Navigate to the project directory**:
   ```bash
   cd diabetics-checkup-app
   
4. **Install the Required dependencies**:
   ```bash
   pip install -r requirements.txt

5. **Run the Streamlit app**:
   ```bash
   streamlit run app.py



