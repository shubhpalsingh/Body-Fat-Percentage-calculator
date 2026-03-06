# Body Fat Percentage Prediction (Regression Project)

This project explores regression models to predict **body fat percentage** from anthropometric measurements like weight, height, and various body circumferences using Python and scikit-learn.
## Dataset
The notebook uses a tabular body composition dataset with **252 rows** and **15 columns**, including:

- Density  
- BodyFat (target: body fat percentage)  
- Age  
- Weight  
- Height  
- Neck  
- Chest  
- Abdomen  
- Hip  
- Thigh  
- Knee  
- Ankle  
- Biceps  
- Forearm  
- Wrist  

Make sure the dataset CSV file is placed in the same directory as the notebook, and update the file path in the data loading cell if necessary.

## Features

The notebook includes:

- Data loading and inspection (head, info, descriptive statistics).  
- Exploratory data analysis using **pandas**, **seaborn**, and **matplotlib**.  
- Train–test split and preprocessing (scaling, label handling if required).  
- Multiple regression models:
  - Linear Regression  
  - Decision Tree Regressor  
  - Random Forest Regressor  
  - Support Vector Regressor (SVR)  
  - K-Nearest Neighbors Regressor (KNN)  
- Model evaluation using metrics such as **R² score** and error measures.

You can extend the notebook with hyperparameter tuning and additional visualizations of predicted vs. actual body fat percentage.

## Requirements

Create a virtual environment (optional) and install the required packages:

```bash
pip install -r requirements.txt
Minimum packages:

pandas

numpy

seaborn

matplotlib

scikit-learn

jupyter

How to Run
Clone this repository:

bash
git clone https://github.com/<your-username>/<your-bofyfat-repo>.git
cd <your-bofyfat-repo>
(Optional) Create and activate a virtual environment:

bash
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS / Linux
source .venv/bin/activate
Install dependencies:

bash
pip install -r requirements.txt
Launch Jupyter Notebook:

bash
jupyter notebook
Open body-mass-index.ipynb (body fat percentage prediction notebook) and run the cells in order.

Project Goals
This notebook is intended as a learning project to practice:

Working with real-valued tabular data.

Building and comparing different regression algorithms in scikit-learn.

Predicting body fat percentage from anthropometric measurements.
