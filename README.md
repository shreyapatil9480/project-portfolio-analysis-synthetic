
# Project Portfolio Analysis

This repository contains a synthetic project portfolio dataset and a corresponding Jupyter notebook that demonstrates exploratory data analysis and predictive modeling. The project is designed for professionals aiming for business analyst, program manager, or data analyst roles. It showcases data analysis skills, visualization techniques, and a simple logistic regression model to predict project success.

## Contents

- **project_portfolio_dataset.csv** — A synthetic dataset with 300 project records. Each record includes project start and end dates, planned and actual durations, budgets, costs, team sizes, complexity scores, risk levels, project status, success indicators, and customer satisfaction scores.
- **analysis_notebook.ipynb** — A Jupyter notebook that performs the following steps:
  1. **Data Loading & Overview**: Loads the dataset and provides an overview of the columns.
  2. **Exploratory Data Analysis**: Computes summary statistics and creates visualizations to understand budget distributions, project statuses, complexity vs. success, and correlations among numerical features.
  3. **Predictive Modeling**: Builds a logistic regression model to predict project success based on numerical features. Includes training/testing splits, standardization, and evaluation metrics.
  4. **Conclusion**: Summarizes key insights and suggests potential extensions.
- **requirements.txt** — Lists the Python dependencies needed to run the notebook.

## Getting Started

To run the analysis:

1. Clone this repository.
2. Install dependencies using pip:

   ```bash
   pip install -r requirements.txt
   ```

3. Launch the Jupyter notebook:

   ```bash
   jupyter notebook analysis_notebook.ipynb
   ```

4. Execute the cells sequentially to reproduce the analysis.

## Dataset Description

The synthetic dataset simulates real-world project portfolios. Columns include:

| Column | Description |
| --- | --- |
| `project_id` | Unique identifier for each project |
| `start_date` | Date the project started |
| `planned_end_date` | Planned project completion date |
| `actual_end_date` | Actual project completion date |
| `planned_duration_days` | Planned duration in days |
| `actual_duration_days` | Actual duration in days |
| `budget_usd` | Planned budget in USD |
| `actual_cost_usd` | Actual cost in USD |
| `team_size` | Number of team members on the project |
| `complexity` | Project complexity score (1–10) |
| `risk_level` | Project risk level (1–5) |
| `status` | Project status (Completed, Ongoing, Cancelled) |
| `success` | Binary indicator of project success (1=successful, 0=not successful) |
| `satisfaction_score` | Customer satisfaction score (1–5) |

## Motivation

This project is intended to enhance your portfolio by demonstrating your ability to:


- Generate and work with structured datasets.
- Perform exploratory data analysis and create meaningful visualizations.
- Build and evaluate predictive models using scikit-learn.
- Document your work clearly and comprehensively in a README and notebook.

Feel free to build on this project by adding new models, interactive dashboards (e.g., using Plotly or Dash), or deeper analyses (such as time-series forecasting or clustering).
## Usage

Follow these steps to run and extend the project:

1. **Environment setup**: Ensure you have Python (>=3.8) and pip installed. Using a virtual environment is recommended.
2. **Install dependencies**: From the repository root, run:

   ```bash
   pip install -r requirements.txt
   ```

3. **Launch the notebook**: Open the Jupyter notebook by running:

   ```bash
   jupyter notebook analysis_notebook.ipynb
   ```

   Then follow the cells sequentially. The notebook will automatically load the synthetic dataset from `project_portfolio_dataset.csv`.

4. **Explore and modify**: Add new exploratory plots or test alternative models. Use the EDA section as a starting point for additional visualizations and insights.

5. **Regenerate data (optional)**: The synthetic data is created within the notebook. To generate a new dataset with different characteristics, edit the data generation code near the top of `analysis_notebook.ipynb` and rerun the cells to produce a new CSV.

6. **Extend the models**: The predictive modeling section uses a logistic regression classifier. Feel free to experiment with other algorithms (e.g., decision trees, random forests, gradient boosting) by replacing the model in the notebook.

This repository is designed to be a complete, out‑of‑the‑box example for demonstrating data analysis and predictive modeling skills in a project management context. Contributions and improvements—such as adding interactive dashboards or more sophisticated machine learning techniques—are welcome.
