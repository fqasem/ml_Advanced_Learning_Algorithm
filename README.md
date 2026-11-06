# Advanced Learning Algorithms

Coursework and Jupyter notebooks for the **Advanced Learning Algorithms** course in the Stanford Online Machine Learning Specialization. The materials cover neural networks, decision trees and ensembles, and practical advice for applying machine learning.

## Project structure

- [`neural_network/`](neural_network/) — Labs on neurons and layers, coffee roasting, derivatives and backpropagation, multiclass classification, ReLU and softmax, model evaluation, and bias and variance. Also includes a Python/PySpark datetime comparison notebook.
- [`decision_trees/`](decision_trees/) — Decision-tree and tree-ensemble labs, a graded lab, and the `heart.csv` dataset used by the notebooks.
- [`Advice_for_Applying_Machine_Learning/`](Advice_for_Applying_Machine_Learning/) — Assignment notebook and supporting files for advice on applying machine learning.

Each directory has its own `requirements.txt`; install dependencies for the directory whose notebooks you plan to run.

## Getting started

The following PowerShell commands create and activate a virtual environment for the neural-network notebooks. Replace `neural_network` with `decision_trees` or `Advice_for_Applying_Machine_Learning` to set up another section.

```powershell
cd neural_network
py -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
python -m pip install jupyter
jupyter lab
```

Open the notebook you want to run in JupyterLab. Some packages, especially TensorFlow, have Python-version and platform requirements; use a Python version supported by the packages in that section if installation fails.

## Notes

- Run notebooks from their section directory so relative paths to data and helper files resolve correctly.
- These are educational course materials and assignments, not a packaged application.
