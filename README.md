# BME3053_Final_Group_6
This repository contains a machine learning model for detecting leukemia using biomarker data. The model implements multiple classifiers (Logistic Regression and Random Forest) to provide reliable predictions.

## 🎥 Final Project YouTube Link

[Watch the final project here](https://youtu.be/kq4cV2U281k?si=KindC__xuNWlLGjv)

## 📋 Prerequisites

Before running the model, ensure you have the following installed:
- Python 3.x
- Jupyter Notebook

## 🔧 Required Libraries

Install the following Python libraries:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

## 📁 Project Structure

- `leukemia_detection_model.ipynb`: Main Jupyter notebook containing the model implementation
- `synthetic_leukemia_biomarkers.csv`: Dataset file (you need to provide your own data file)

## 🚀 How to Run the Model

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd leukemia-detection-model
   ```

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

4. **Open and Run the Notebook**
   - Open `leukemia_detection_model.ipynb`
   - Select "Kernel" > "Restart & Run All" to execute all cells

## 📊 Data Requirements

Your input data file should be in CSV format with the following:
- A column indicating leukemia status (will be auto-detected if contains 'leukemia' and 'status' in the name)
- Patient ID column (optional, will be auto-detected if contains 'id')
- Biomarker measurements as additional columns

## 🔄 Model Workflow

1. **Data Loading and Exploration**
   - Automatic detection of target and ID columns
   - Data visualization and statistical analysis
   - Handling of missing values

2. **Data Preprocessing**
   - Feature scaling
   - Categorical variable encoding
   - Feature selection

3. **Model Training**
   - Training multiple models (Logistic Regression and Random Forest)
   - Hyperparameter tuning using GridSearchCV
   - Class weight balancing

4. **Model Evaluation**
   - Performance metrics calculation
   - Confusion matrix visualization
   - Classification report generation

5. **Making Predictions**
   - Interactive input for new patient data
   - Predictions from multiple models
   - Human-readable results

## 💻 Using the Model for Predictions

1. Run all notebook cells until you reach the prediction section
2. When prompted, enter the required biomarker values
3. The model will provide predictions from both classifiers

## 📈 Model Performance Metrics

The model provides the following metrics:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
## 🔬 Synthetic Dataset

This project utilizes synthetic data for development and testing purposes. Using synthetic data offers several advantages:

1. **Privacy Protection**
   - No real patient data is exposed
   - Complies with healthcare data protection regulations
   - Eliminates risk of personal information disclosure

2. **Data Availability**
   - Overcomes the scarcity of real medical datasets
   - Allows for larger training datasets
   - Enables testing with various disease patterns

3. **Controlled Testing**
   - Known ground truth for all cases
   - Ability to test edge cases and rare conditions
   - Perfect for model validation and testing

4. **Educational Purpose**
   - Ideal for learning and demonstration
   - No ethical concerns regarding data usage
   - Easy to share and reproduce results

The synthetic dataset maintains the statistical properties and relationships found in real leukemia biomarker data while ensuring complete privacy and control over the data distribution.
