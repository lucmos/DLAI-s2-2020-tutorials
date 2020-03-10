# Deep Learning & Applied AI: Tutorials

This repository contains the code and notebooks shown during the course lab tutorials

## Logistics

**Lecturer:** Prof. Emanuele Rodolà

**Course website:** [DLAI-s2-2020](https://erodola.github.io/DLAI-s2-2020/)

**Assistants:** Dr. Luca Moschella, Dr. Antonio Norelli

## Tutorials

| **Date**   | **Topic**      | **Code**                                                                                                                | **Open in Colab**                                                                                                                                                                              |
| ---------- | -------------- | ----------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|            |                |
| Wed 4 Mar  | Tensors basics | [notebook](https://nbviewer.jupyter.org/github/lucmos/DLAI-s2-2020-tutorials/blob/master/01/01_Tensor_basics.ipynb)     | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lucmos/DLAI-s2-2020-tutorials/blob/master/01/01_Tensor_basics.ipynb)     |
|            |                |
| Wed 11 Mar |                | [notebook](https://nbviewer.jupyter.org/github/lucmos/DLAI-s2-2020-tutorials/blob/master/02/02_Tensor_operations.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lucmos/DLAI-s2-2020-tutorials/blob/master/02/02_Tensor_operations.ipynb) |
|            |                |


## Running local notebooks

Clone repository, install dependencies and ipython kernel:

```bash
git clone git@github.com:lucmos/DLAI-s2-2020-tutorials.git
cd DLAI-s2-2020-tutorials
poetry install
poetry run ipython kernel install --name "DLAI-s2-2020-tutorials" --user
poetry run jupyter notebook
```
