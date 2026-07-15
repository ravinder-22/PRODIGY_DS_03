# 🌳 Decision Tree Classifier – Customer Purchase Prediction

**Prodigy InfoTech Data Science Internship – Task 03**

## 📌 Task Overview
Build a **Decision Tree Classifier** to predict whether a customer will purchase a product or service (subscribe to a term deposit), based on their **demographic and behavioral data**. The model is trained on the **Bank Marketing dataset** from the UCI Machine Learning Repository, which contains data from direct marketing campaigns (phone calls) of a Portuguese banking institution.

## 📂 Dataset
- **Source:** [UCI Machine Learning Repository – Bank Marketing Dataset](https://archive.ics.uci.edu/dataset/222/bank+marketing)
- **Sample Dataset:** [Prodigy-InfoTech/data-science-datasets – Task 3](https://github.com/Prodigy-InfoTech/data-science-datasets/tree/main/Task%203)
- **Target Variable:** `y` — whether the client subscribed to a term deposit (`yes` / `no`)

### Key Features
| Feature | Description |
|---|---|
| `age` | Age of the customer |
| `job` | Type of occupation |
| `marital` | Marital status |
| `education` | Education level |
| `default` | Has credit in default? |
| `balance` | Average yearly account balance (€) |
| `housing` | Has a housing loan? |
| `loan` | Has a personal loan? |
| `contact` | Contact communication type |
| `duration` | Last contact duration (seconds) |
| `campaign` | Number of contacts during this campaign |
| `pdays` | Days since last contacted from a previous campaign |
| `previous` | Number of contacts before this campaign |
| `poutcome` | Outcome of the previous marketing campaign |

## 🛠️ Tech Stack
- **Language:** Python 3.x
- **Libraries:**
  - `pandas`, `numpy` – data manipulation
  - `matplotlib`, `seaborn` – visualization
  - `scikit-learn` – model building & evaluation

## 🔍 Project Workflow
1. **Data Loading & Cleaning** – handle missing values, drop duplicates, fix inconsistent entries
2. **Exploratory Data Analysis (EDA)** – understand feature distributions and their relationship with the target
3. **Data Preprocessing** – encode categorical variables (Label/One-Hot Encoding), handle class imbalance
4. **Train-Test Split** – split data into training and testing sets
5. **Model Building** – train a `DecisionTreeClassifier` from scikit-learn
6. **Model Evaluation** – accuracy, precision, recall, F1-score, confusion matrix
7. **Visualization** – plot the decision tree and feature importances

## 📊 Results
The trained decision tree model classifies customers as likely or unlikely to subscribe to a term deposit, and highlights the most influential features (such as call duration, previous campaign outcome, and contact type) driving that decision.

## 🚀 How to Run
```bash
# Clone the repository
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook decision_tree_classifier.ipynb
```

## 📁 Repository Structure
```
├── data/
│   └── bank-marketing.csv
├── decision_tree_classifier.ipynb
├── requirements.txt
└── README.md
```

## 📈 Future Improvements
- Hyperparameter tuning (max_depth, min_samples_split) using GridSearchCV
- Compare performance with Random Forest / Gradient Boosting models
- Handle class imbalance using SMOTE or class weighting
- Deploy the model as a simple web app

## 🙌 Acknowledgements
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/222/bank+marketing) for the Bank Marketing dataset
- [Prodigy InfoTech](https://prodigyinfotech.dev/) for the internship task

## 📬 Connect
If you found this project useful, feel free to ⭐ the repo or connect with me for feedback and discussions on data science!

- GitHub: @Raj1729verma (https://github.com/ravinder-22)
- LinkedIn: Ravinder Singh (https://www.linkedin.com/in/ravinder-singh-9033b22a8)

---
*This project was completed as part of the Prodigy InfoTech Data Science Internship (Task 03).*
