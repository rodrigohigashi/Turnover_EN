📌 Employee Turnover Analysis

This project uses a Decision Tree to classify whether an employee will have turnover (leave the company) or not, based on their characteristics.

📊 Objective

The goal is to build a predictive model capable of identifying patterns and assisting in decision-making regarding talent retention.

🔍 Exploratory Data Analysis (EDA)

Before training the model, the aed.py file performs an automated exploratory analysis, including:

Pandas Profiling: Generates a detailed report about the dataset, with descriptive statistics and visualizations.
Information Value (IV): Calculates the importance of independent variables in predicting the target variable (turnover).
Bivariate Analysis: Examines the relationship between independent variables and the target variable.
How to run the exploratory analysis:

Run the aed.py script to obtain a complete exploratory analysis report.

python aed.py
The script will generate a pandas profiling report and other analyses in the output directory.

🚀 How to Run the Project

Clone this repository:

git clone https://github.com/rodrigohigashi/Turnover.git
cd turnover-analysis
Create and activate a virtual environment (optional, but recommended):

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install the dependencies:

pip install -r requirements.txt
Run the EDA script:

python aed.py
After the exploratory analysis, run the decision tree model:

python main.py
📈 Metrics Used

The model is evaluated by several classification metrics:

Accuracy
Precision
Recall (Sensitivity)
F1-score
Confusion Matrix
Gini Index
📊 Visualizations

The project includes two ways to visualize the decision tree:

plot_tree (default sklearn visualization)
dtreeviz (more detailed and interpretable visualization)
Example of a generated tree:

📜 License

This project is free for educational and study purposes.

