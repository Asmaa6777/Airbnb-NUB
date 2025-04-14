# 📌 Airbnb New User Booking Prediction

## 🚀 Objective
Predict where a new Airbnb user will book their first trip.

## 📁 Folder Structure
```
airbnb-new-user-prediction/
│
├── data/                  # Contains raw and processed data
│   ├── raw/               # Original dataset files
│   └── processed/         # Cleaned and preprocessed datasets
│
├── notebooks/             # Jupyter notebooks for each step
│   ├── 01_data_loading.ipynb    # Data loading and initial inspection
│   ├── 02_eda.ipynb             # Exploratory data analysis
│   ├── 03_preprocessing.ipynb   # Data preprocessing pipeline
│   ├── 04_model_training.ipynb  # Model training and tuning
│   ├── 05_evaluation.ipynb      # Model evaluation and selection
│
├── models/                # Saved ML models
│
├── outputs/               # Figures, reports, etc.
│
├── requirements.txt       # Python dependencies
└── README.md              # Project overview
```

## 🧪 How to Run the Notebooks

1. Clone this repository:
   ```
   git clone [your-repo-url]
   cd AIProjectDSC
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Run the notebooks in sequential order:
   - Start with `01_data_loading.ipynb` to understand the dataset
   - Proceed to `02_eda.ipynb` for exploratory data analysis
   - Continue with `03_preprocessing.ipynb` to prepare data for modeling
   - Use `04_model_training.ipynb` to train various models
   - Finish with `05_evaluation.ipynb` to evaluate model performance

## 📊 Example Outputs
Key insights and visualizations from this project include:
- Demographic analysis of Airbnb users
- Destination popularity by user characteristics
- Feature importance in predicting booking destinations
- Model performance metrics and comparisons

## 📦 Requirements
See requirements.txt for a complete list of dependencies.

## 🛠 Tech Stack
- Python
- pandas
- scikit-learn
- matplotlib/seaborn
- Jupyter

## 🧠 What I Learned
- Working with imbalanced multi-class classification problems
- Feature engineering for user behavior prediction
- Model selection and evaluation techniques
- Handling large datasets with efficient preprocessing

## 🙌 Acknowledgments
- Airbnb for providing the dataset
- Kaggle competition platform

**Note:** The sessions.csv file (602MB) is not included in this repository due to GitHub's 100MB file size limit. Please obtain this file separately.