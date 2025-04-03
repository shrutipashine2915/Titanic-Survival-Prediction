# Titanic Survival Prediction Using Machine Learning

This project aims to predict the survival of passengers aboard the Titanic using machine learning techniques. The dataset is processed, visualized, and analyzed to build a predictive model.

## Requirements

Ensure you have Python installed along with the following packages:

```bash
pip install pandas numpy seaborn matplotlib
```

## Project Structure

- `Titanic.ipynb`: Jupyter Notebook containing data analysis, visualizations, and model training.
- `data/train.csv`: Training dataset used for building the model.
- `data/test.csv`: Testing dataset used for evaluating the model.

## Usage

1. Clone the repository and navigate to the project directory.
2. Install the required packages.
3. Run the Jupyter Notebook:

```bash
jupyter notebook Titanic.ipynb
```

## Data Loading

The training and testing datasets are loaded using:

```python
import pandas as pd

train_data = pd.read_csv('data/train.csv')
test = pd.read_csv('data/test.csv')
```

## Exploratory Data Analysis (EDA)

Various data visualization techniques are used to understand the data distribution:

- Histograms for numerical columns: `Age`, `SibSp`, `Parch`, `Fare`
- Bar plots to compare `Pclass` vs. `Fare` with respect to `Survived`

## Next Steps

- Data Preprocessing
- Feature Engineering
- Model Training & Evaluation

## Acknowledgments

This project is inspired by the Kaggle Titanic competition.

