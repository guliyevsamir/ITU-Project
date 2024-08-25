# ITU Project: Socioeconomic Status Classification

This repository contains the project developed as part of the Certificate Program on Big Data and Business Analytics organized by Istanbul Technical University in co-partnership with Mindset Institute.

## Project Overview

This project is centered around the classification of socioeconomic status (SES) using various data-driven techniques. The goal was to explore and implement different machine learning models to accurately predict SES based on provided features and to identify key factors influencing these predictions.

## Repository Contents

- **`adult.csv`**: The dataset used for the project, containing demographic and socioeconomic features.
- **`adult-census-income-metadata.json`**: Metadata for the dataset including feature descriptions and other relevant information.
- **`Socioeconomic Status Classification.ipynb`**: Jupyter notebook with the code, data preprocessing, model training, and analysis.
- **`Socioeconomic Status Classification.html`**: HTML version of the notebook for easy viewing without requiring a Jupyter environment.
- **`Socioeconomic Status Classification.pdf`**: PDF version of the report summarizing the project's methodology, analysis, and results.
- **`Socioeconomic Status Classification.pptx`**: PowerPoint presentation summarizing the project's key points and results.

## Data

The data used in this project is sourced from the UCI Machine Learning Repository and is publicly available. It includes demographic and socioeconomic features for predicting whether an individual's income exceeds $50K per year.

## Methodology

1. **Data Preprocessing**: Cleaning, normalizing, and encoding data.
2. **Exploratory Data Analysis (EDA)**: Visualizing data distributions and relationships.
3. **Modeling**: Implementing machine learning models including Logistic Regression, XGBoost, and Decision Trees.
4. **Evaluation**: Comparing models using accuracy, precision, recall, and F1-score.

## Results

The XGBoost model with feature selection emerged as the top-performing model, highlighting the significance of feature engineering in predictive modeling.

## Installation

To run the analysis locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/guliyevsamir/ITU-Project.git
   cd ITU-Project
   ```
2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scriptsctivate`
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter notebook:
   ```bash
   jupyter notebook "Socioeconomic Status Classification.ipynb"
   ```

## Usage

Explore the analysis in the Jupyter notebook or view the HTML/PDF versions for a detailed overview of the project.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any major changes. For minor changes, you can open an issue.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or issues, feel free to contact me at samir.guliyev@hotmail.com.
