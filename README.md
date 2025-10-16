# DeepLearning — Basics of Deep Learning

A tiny, hands-on collection of Jupyter Notebooks covering basic deep learning concepts.

Basics
---
- [Intro to neuron](/notebooks/single_neuron.ipynb)
- [Intro to binary classification](/notebooks/binary_classification.ipynb)
- [deep neural networks](/notebooks/deep_neural_network.ipynb)
- [stohastic gradient descent](/notebooks/stohastic_gradient_descent.ipynb)
- [dropout and batch normalization](/notebooks/dropout_batch_normalization.ipynb)
- [overfitting and underfitting](/notebooks/overfitting_underfitting.ipynb)
---

Analysis
---
- [student exam score analysis](/analysis/student-exam-score-analysis.ipynb)

## Installation

first clone the repository using:
```bash
git clone https://github.com/Rengeten1/DeepLearning.git
```
To make a virtual environment:
```bash
python -m venv .venv
source .venv/bin/activate
```

if using CPU use:
```python 
pip install -r requirements.txt 
```
if using GPU then after running above command run this:
```bash
pip install -r requirements.txt 
pip install tensorflow[and-cuda]
```

## Data

[**dl-course-data**](https://www.kaggle.com/datasets/ryanholbrook/dl-course-data)

[**student-exam-score-dataset-analysis**](https://www.kaggle.com/datasets/grandmaster07/student-exam-score-dataset-analysis)