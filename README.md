# Predict the Success of Bank Telemarketing

## Project Description
This project aims to predict the success of a bank telemarketing campaign using machine learning classification models. The dataset consists of customer information and telemarketing outcomes. The goal is to analyze the data, build predictive models, and evaluate their performance using various metrics.

## Structure
```
Predict-Bank-Telemarketing-Success/
├── data/               # contains 2 datafiles train.csv and test.csv
├── notebooks/          # contains the python notebook
│   └── bank_telemarketing_classification.ipynb
├── README.md           # Describes the project
├── requirements.txt    # Python dependencies
└── LICENSE             # Project license
```

## How to Run
1. Clone the repository:
   ```
   git clone https://github.com/AmmarSajjid/Banking-Telemarketing-Success-Prediction.git
   ```
2. Navigate to the directory:
   ```
   cd Banking-Telemarketing-Success-Prediction
   ```
3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
4. Open the notebook:
   ```
   jupyter notebook notebooks/bank_telemarketing_classification.ipynb
   ```

## Dataset
- **Source:** [[Kaggle Competition](https://www.kaggle.com/competitions/predict-the-success-of-bank-telemarketing/overview)]
- **Features:**
  - `age`: Age of the client.
  - `job`: Type of job (e.g., admin, technician, entrepreneur).
  - `marital`: Marital status (e.g., married, single, divorced).
  - `education`: Level of education.
  - `default`: Whether the client has credit in default.
  - `balance`: Average yearly balance in euros.
  - `housing`: Whether the client has a housing loan.
  - `loan`: Whether the client has a personal loan.
  - `contact`: Contact communication type.
  - `day`: Last contact day of the month.
  - `month`: Last contact month of the year.
  - `duration`: Last contact duration, in seconds.
  - `campaign`: Number of contacts performed during this campaign.
  - `pdays`: Days since the client was last contacted.
  - `previous`: Number of contacts performed before this campaign.
  - `poutcome`: Outcome of the previous marketing campaign.
- **Target:**
  - `y`: Success of the telemarketing campaign (`yes`/`no`).

## Models Used
- Logistic Regression
- Decision Trees
- Random Forest
- Stochastic Gradient Boosting
- Support Vector Machines
- XG Boost

## Results
- **Best model:** [XG Boost]

## Evaluation
- Models were evaluated using a train-test split and cross-validation.
- The performance of each model was measured using classification metrics such as precision, recall, and F1-score.

## Conclusion
This project demonstrates the use of machine learning models to predict the success of bank telemarketing campaigns. By analyzing customer attributes and campaign details, predictive models can assist in identifying strategies to improve campaign success rates.

## License
[MIT License](LICENSE)

## Acknowledgments
- Dataset: Kaggle
- Tools: Python, Scikit-learn, Pandas, Matplotlib, Seaborn

## Contact
For any questions or suggestions, please reach out to:
- **Email:** ammar@atbmt.com
- **Linked In:** [Ammar Sajjid](https://www.linkedin.com/in/ammarsajjid/)
