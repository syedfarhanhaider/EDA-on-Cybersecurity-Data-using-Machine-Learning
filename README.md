# Cybersecurity Attack Analysis & TCP Port Vulnerability Detection

This project focuses on analyzing cybersecurity attack data to identify trends, patterns, and vulnerabilities associated with TCP ports. The goal is to leverage machine learning models to predict attack types and uncover insights for cybersecurity defense.

## Project Objective

The primary objective is to extract insights from cybersecurity attack data and TCP port logs to:
1. Analyze attack patterns.
2. Identify high-risk TCP ports.
3. Predict potential attack types using machine learning.

## Key Components

### 1. Data Sources:
- **Cybersecurity_attacks.csv**: Includes historical data on various cybersecurity incidents (attack type, target, and timestamp).
- **TCP-ports.csv**: Contains data on TCP port activity, mapping port numbers to specific attack events.

### 2. Data Cleaning:
- **Data Preprocessing**: Addressed missing values, inconsistent entries, and normalized features for model readiness.
- **TCP Port Mapping**: Cross-referenced TCP port activity with attack records to highlight high-risk ports.

### 3. Exploratory Data Analysis (EDA):
- **Attack Frequency Analysis**: Identified the most frequent attack types across different TCP ports.
- **Port Vulnerability Analysis**: Highlighted the TCP ports most targeted by specific attack types.

### 4. Machine Learning Models:
- **Models Used**: Random Forest, Logistic Regression, and Decision Trees.
- **Target**: Attack type classification based on TCP port, attack patterns, and metadata.
- **Evaluation**: Model performance was assessed using accuracy, precision, recall, and F1 score.

### 5. Results:
- **High-Risk TCP Ports**: Pinpointed the most vulnerable ports based on frequency and attack severity.
- **Prediction Accuracy**: Achieved over 85% accuracy in predicting the type of cyberattack given a set of input features.

## Tools & Libraries

- **Python** for data processing and modeling.
- **pandas**, **numpy** for data manipulation.
- **matplotlib**, **seaborn** for visualizing data trends.
- **scikit-learn** for building and evaluating machine learning models.
- **Jupyter** Notebook for documenting and running the project.

## Project Workflow

1. **Data Ingestion**: Load and inspect both attack and TCP port datasets.
2. **Data Preprocessing**: Clean and prepare datasets for analysis and modeling.
3. **Exploratory Data Analysis (EDA)**: Analyze patterns in the attack data and visualize port vulnerabilities.
4. **Model Training**: Build classification models to predict attack types.
5. **Results Interpretation**: Evaluate the model's predictions and visualize the attack trends.

## Key Insights

- **Top Vulnerabilities**: TCP ports such as 22 (SSH), 80 (HTTP), and 443 (HTTPS) were the most targeted, with specific attack types focusing on these ports.
- **Model Accuracy**: Predictive models achieved significant accuracy, helping to foresee potential future attack trends.
- **Actionable Insights**: Reinforcing protection on these high-risk TCP ports can significantly reduce vulnerabilities.

## Running the Project

### Prerequisites

Install the necessary dependencies:
```bash
pip install -r requirements.txt

### Steps to Run

1. Clone the repository:
```bash
git clone https://github.com/your_username/cybersecurity-attack-analysis.git

2. Navigate to the directory:
```bash
cd cybersecurity-attack-analysis

3. Open the Jupyter Notebook:
```bash
jupyter notebook Cybersecurity_Project.ipynb

4. Run the cells to execute the analysis and visualize results.

## Future Enhancements

- **Real-time Data**: Implement real-time analysis of ongoing attacks.
- **Anomaly Detection**: Integrate models for detecting anomalous activity in network traffic.
- **Expanded Data**: Broaden the dataset to include more varied attack types and network logs.

## Contribution

Contributions are welcome! Open an issue or submit a pull request for any suggestions or improvements.
