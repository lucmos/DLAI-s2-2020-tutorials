# Deep Learning & Applied AI: Tutorials

This repository contains the code and notebooks shown during the course lab tutorials

## Logistics

**Lecturer:** Prof. Emanuele Rodolà

**Course website:** [DLAI-s2-2020](https://erodola.github.io/DLAI-s2-2020/)

**Assistants:** Dr. Luca Moschella, Dr. Antonio Norelli

## Tutorials

| **Date**   | **Topic**                                                 | **Code**                                                                                                                                      | **Open in Colab**                                                                                                                                                                                                                     |
| ---------- | --------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|            |                                                           |
| Wed 4 Mar  | Tensors basics                                            | [notebook](https://nbviewer.jupyter.org/github/lucmos/DLAI-s2-2020-tutorials/blob/master/01/01_Tensor_basics.ipynb)                           | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lucmos/DLAI-s2-2020-tutorials/blob/master/01/01_Tensor_basics.ipynb)                                            |
|            |                                                           |
| Wed 11 Mar | Tensor operations                                         | [notebook](https://github.com/lucmos/DLAI-s2-2020-tutorials/blob/master/02/02_Tensor_operations.ipynb)                                        | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lucmos/DLAI-s2-2020-tutorials/blob/master/02/02_Tensor_operations.ipynb)                                        |
|            |                                                           |
| Wed 18 Mar | Linear models and Pytorch Datasets                        | [notebook](https://github.com/lucmos/DLAI-s2-2020-tutorials/blob/master/03/03_Linear_models_and_Pytorch_Datasets.ipynb)                       | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lucmos/DLAI-s2-2020-tutorials/blob/master/03/03_Linear_models_and_Pytorch_Datasets.ipynb)                       |
|            |                                                           |
| Wed 25 Mar | Logistic Regression and Optimization                      | [notebook](https://github.com/lucmos/DLAI-s2-2020-tutorials/blob/master/04/4_Logistic_Regression_and_Optimization.ipynb)                      | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lucmos/DLAI-s2-2020-tutorials/blob/master/04/4_Logistic_Regression_and_Optimization.ipynb)                      |
|            |                                                           |
| Wed 1 Apr  | Autograd and Modules                                      | [notebook](https://github.com/lucmos/DLAI-s2-2020-tutorials/blob/master/05/5_Autograd_and_Modules.ipynb)                                      | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lucmos/DLAI-s2-2020-tutorials/blob/master/05/5_Autograd_and_Modules.ipynb)                                      |
|            |                                                           |
| Wed 8 Apr  | Convolutional Neural Networks                             | [notebook](https://github.com/lucmos/DLAI-s2-2020-tutorials/blob/master/06/6_Convolutional_Neural_Networks.ipynb)                             | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lucmos/DLAI-s2-2020-tutorials/blob/master/06/6_Convolutional_Neural_Networks.ipynb)                             |
|            |                                                           |
| Wed 29 Apr | Uncertainty, regularization and the deep learning toolset | [notebook](https://github.com/lucmos/DLAI-s2-2020-tutorials/blob/master/07/7_Uncertainty,_regularization_and_the_deep_learning_toolset.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lucmos/DLAI-s2-2020-tutorials/blob/master/07/7_Uncertainty,_regularization_and_the_deep_learning_toolset.ipynb) |
|            |                                                           |

## Running local notebooks

Clone repository, install dependencies and ipython kernel:

```bash
git clone git@github.com:lucmos/DLAI-s2-2020-tutorials.git
cd DLAI-s2-2020-tutorials
poetry install
poetry run ipython kernel install --name "DLAI-s2-2020-tutorials" --user
poetry run jupyter notebook
```
