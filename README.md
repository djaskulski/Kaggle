Introduction
------------
This is my repository for working with Kaggle competitions.
```
Competition_name/
  -jupyter_notebook.ipynb
  -submission.csv
  -train_data.csv
  -train_data.csv
```



Requirements
------------
src/environment.yml

```
name: kaggle_env
channels:
 - conda-forge
 - defaults
dependencies:
 - python == 3.8.5
 - numpy 
 - pandas
 - matplotlib
 - seaborn
 - scikit-learn
 - jupyterlab
```



Installation
------------
[Miniconda installation](https://conda.io/projects/conda/en/latest/user-guide/install/index.html)

In Anaconda prompt:
[Create conda env from file](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file)\
conda env create -f environment.yml



Usage
-----
In Anaconda prompt:\
conda activate kaggle_env\
jupyter lab
