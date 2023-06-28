# recommender-systems-project

The goal of the project was to create a recommendation system that, for hotel booking data, would be more effective than
Amazon's recommender (HR@10 evaluation).

## Preparing your computer

1. Install [Anaconda](https://www.anaconda.com/products/individual) with Python 3.8.


2. Install [Git](https://git-scm.com/downloads).


3. Install [PyCharm](https://www.jetbrains.com/pycharm/) (community version).

4. Clone the repo.

```
$ git clone git@github.com:korzepadawid/nn-recommender.git && cd nn-recommender
```

5. Create a Conda environment.

```
 $ conda env create --name rs-class-proj-env -f environment.yml
```

6. Activate the virtual environment, you've just created.

```
$ conda activate rs-class-proj-env
```

7. Run the notebook.

```
$ jupyter notebook
```

## The used dependecies.

- NumPy
- Pandas
- scitkitlearn
- hyperopt
- PyTorch

## The results.

| Model| Result HR@10 |
|--|--|
| **NN Tuned** | 0.247794 |
| Amazon Recommender | 0.221996 |
