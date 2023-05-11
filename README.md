# Python_ML_2023
Machine learning in Python 2023 - For TCDS students

## Installation

Follow these instructions. This works independent of any existing pooltool conda environments you may or may not have.

```bash
conda deactivate
conda env remove --name python_ml_2023
conda create -y -n python_ml_2023 python=3.9.0
conda activate python_ml_2023
```

Verify you're running `3.9.0`

```
$ python
Python 3.9.10 (default, May 19 2021, 11:01:55)
[Clang 10.0.0 ] :: Anaconda, Inc. on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> exit()
```

Install requirements:

Using pip:

```bash
pip install -r requirements.txt
```

Using conda:

```bash
conda config --append channels conda-forge
conda install --file requirements.txt
```

Create a jupyterlab kernel for the environment we've just created:
```bash
python -m ipykernel install --user --name=python_ml_2023
```
