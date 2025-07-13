# 📈 Bitcoin Stock Market Price Prediction

## 🧠 Project Objective
The goal of this project is to predict the **opening prices of Bitcoin** using historical financial data. This is achieved by building and evaluating various **regression models**.

---

## 📂 Dataset
- The dataset used contains **historical Bitcoin prices**, with a focus on **daily opening prices**.
- Data preprocessing steps were performed to clean and prepare the dataset for training.

---

## 🔧 Tools & Technologies Used
- **Language**: Python  
- **Environment**: Jupyter Notebook  
- **Libraries**: 
  - `pandas` 
  - `numpy` 
  - `matplotlib` 
  - `seaborn` 
  - `scikit-learn`

---

## 📊 Methodology

### 1. Data Cleaning & Exploration
- Checked for missing/null values and handled them.
- Converted date columns to appropriate datetime formats.
- Visualized trends and patterns using `matplotlib` and `seaborn`.

### 2. Feature Selection
- Selected relevant columns, focusing on the `Open` price.
- Created lag-based features (if applicable) to simulate time series input.

### 3. Model Building
- Split the dataset into training and testing sets using `train_test_split`.
- Applied regression models to predict the Bitcoin opening price.

### 4. Model Evaluation
- Evaluated models using:
  - **Mean Squared Error (MSE)**
  - **Root Mean Squared Error (RMSE)**
  - **R² Score**

### 5. Visualization
- Plotted **actual vs predicted** Bitcoin opening prices for visual analysis.

---

## 📈 Output
- Models were trained to predict the **Bitcoin opening price**.
- Plots and metrics showed the comparison between predicted and actual values.
