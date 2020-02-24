Installation
------------

Clone repository, install dependencies and ipython kernel:

.. code:: bash

    git clone https://github.com/lucmos/pytorch-tutorial
    cd pytorch-tutorial
    poetry install
    poetry run ipython kernel install --name "pytorch-tutorial" --user
    poetry run jupyter notebook
