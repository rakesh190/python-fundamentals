# Python Fundamentals for Machine Learning

A structured, hands-on course covering Python essentials for ML — from basics to scikit-learn pipelines. Each module is a Jupyter notebook with concept explanations, worked examples, exercises, and challenge problems.

---

## Modules

| # | Module | Topics |
|---|--------|--------|
| 01 | Python Basics | Variables, control flow, functions, error handling |
| 02 | Data Structures | Lists, dicts, sets, comprehensions, generators |
| 03 | NumPy | Arrays, broadcasting, linear algebra, gradient descent |
| 04 | Pandas | DataFrames, feature engineering, EDA pipeline |
| 05 | Visualization | Matplotlib, Seaborn, ROC curve, confusion matrix |
| 06 | Statistics for ML | Distributions, hypothesis testing, bias-variance tradeoff |
| 07 | Scikit-learn | Pipelines, cross-validation, GridSearchCV, model evaluation |
| 08 | OOP for ML | Classes, inheritance, custom sklearn transformers & estimators |

---

## Requirements

- Python 3.9+
- Anaconda (recommended) or pip

### Install dependencies

**With Anaconda (recommended):**
```bash
conda install numpy pandas matplotlib seaborn scikit-learn jupyterlab scipy
```

**With pip:**
```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyterlab scipy
```

---

## Running the Project

### 1. Clone the repository

```bash
git clone https://github.com/rakesh190/python-fundamentals.git
cd python-fundamentals
```

### 2. Start JupyterLab

```bash
jupyter lab
```

This will print a URL like:

```
http://localhost:8888/?token=abc123...
```

Open that URL in your browser.

> **If it asks for a token or password**, copy the full URL from the terminal output (including `?token=...`) and paste it into your browser. Alternatively, run this command to see the URL:
> ```bash
> jupyter server list
> ```

### 3. Open a notebook

In JupyterLab, use the file browser on the left to navigate into any module folder and open the `.ipynb` file.

---

## How to Use Each Notebook

Each notebook follows this structure:

1. **Concept** — explanation of the topic with context for ML
2. **Example** — fully worked code demonstrating the concept
3. **Exercise** — a problem for you to solve (try before looking at the solution!)
4. **Solution** — reference solution in the next cell
5. **Challenge** — a harder problem combining multiple concepts

> Work top to bottom. Run each cell with `Shift + Enter`.

---

## Recommended Learning Order

Work through the modules in order (01 → 08). Each builds on the previous:

```
Python Basics → Data Structures → NumPy → Pandas
                                              ↓
                         OOP ← Scikit-learn ← Visualization ← Statistics
```

---

## Project Structure

```
python-fundamentals/
├── 01_python_basics/
│   └── 01_python_basics.ipynb
├── 02_data_structures/
│   └── 02_data_structures.ipynb
├── 03_numpy/
│   └── 03_numpy.ipynb
├── 04_pandas/
│   └── 04_pandas.ipynb
├── 05_visualization/
│   └── 05_visualization.ipynb
├── 06_statistics/
│   └── 06_statistics_for_ml.ipynb
├── 07_scikit_learn/
│   └── 07_scikit_learn.ipynb
└── 08_oop/
    └── 08_oop_for_ml.ipynb
```
