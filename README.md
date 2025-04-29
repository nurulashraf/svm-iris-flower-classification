# SVM Iris Flower Classification

This project uses a Support Vector Machine (SVM) model to classify Iris flowers into three species, *Setosa*, *Versicolor*, and *Virginica*, based on features such as sepal and petal length and width. The dataset is the classic Iris dataset from scikit-learn.

---

## Project Structure

- **`notebooks/`**: Jupyter notebooks for data analysis, feature engineering, and model building.
- **`README.md`**: Project overview and usage instructions.

---

## Features

- Loads and explores the Iris dataset
- Preprocesses data and splits into train/test sets
- Trains an SVM classifier using scikit-learn
- Evaluates model performance (accuracy, confusion matrix)
- Saves the trained model using pickle
- Easy to modify for experimenting with other models

---

## Tools & Libraries Used

- Python 3.x
- Jupyter Notebook
- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn
- pickle

---

## How to Use

### 1. Clone the repository

```bash
git clone https://github.com/nurulashraf/svm-iris-flower-classification.git
cd svm-iris-flower-classification
```

### 2. Create a virtual environment (optional but recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the notebook

Open `svm_iris_flower_classification.ipynb` in Jupyter Notebook or JupyterLab and run the cells.

---

## License

This project is licensed under the [MIT License](LICENSE).
