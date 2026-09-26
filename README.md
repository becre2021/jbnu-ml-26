# jbnu-ml-26

Machine learning practice notebooks for weeks 2–4, progressing from linear regression to binary and multiclass classification with PyTorch. Each notebook introduces the data, defines a model and loss, implements gradient descent manually, and visualizes the results.

## Notebooks

| Week | Notebook | Dataset | Main topics |
| --- | --- | --- | --- |
| 2 | [Linear regression](week2_linear_reg.ipynb) | 50 noisy synthetic samples | Squared error, closed-form solution, gradient descent |
| 3 | [Logistic regression](week3_logistic_reg.ipynb) | 50 synthetic binary labels | Sigmoid, binary cross-entropy, classification threshold |
| 4 | [Multiclass classification](week4_multicls_classification.ipynb) | MNIST handwritten digits | Softmax, multiclass cross-entropy, mini-batch training |



## Saved figures

Running the visualization cells creates these files:

| Week | Output |
| --- | --- |
| 2 | `gd_vs_closed_form.png` |
| 3 | `logistic_gd_trajectory.png` |
| 4 | `multiclass_gd_trajectory.png`, `multiclass_mnist_predictions.png` |
