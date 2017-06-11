## Project Contents

This project contains the following files:

- `boston_housing.ipynb`: Jupyter notebook containing project code.
- `housing.csv`: The project dataset. You'll load this data in the
  notebook.
- `visuals.py`: This Python script provides supplementary visualizations
  for the project.
- `boston_housing.ipynb`: project notebook (Jupyter - Python 3.5)
- `report.html`: A **HTML** export of the project notebook
- `project_discription.md`: been provided with the project files which
  may contain additional necessary information or instruction for the
  project.
- `project_discription.md`: Predicting Boston Housing Prices project
  rubric.

## Requisites


### Software and Libraries

This project requires **Python 2.7** and the following Python libraries
installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute a
[Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that
you install the [Anaconda](http://continuum.io/downloads) distribution
of Python, which already has the above packages and more included. Make
sure that you select the Python 2.7 installer and not the Python 3.x
installer.

### Data

This dataset is a modified version of the Boston Housing dataset found
on the
[UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Housing).
It consists of 489 data points, with each datapoint having 3 features.

**Features**
1.  `RM`: average number of rooms per dwelling
2. `LSTAT`: percentage of population considered lower status
3. `PTRATIO`: pupil-teacher ratio by town

**Target Variable**
1. `MEDV`: median value of owner-occupied homes

### Code

Code is provided in the `boston_housing.ipynb` notebook file.
It requires the included `visuals.py` Python file and the `housing.csv`
dataset file to work.

Note that the code included in `visuals.py` is meant to be used
out-of-the-box. If you are interested in how the visualizations are
created in the notebook, please feel free to explore this Python file.

### Run

In a terminal or command window, navigate to the top-level project
directory `boston_housing/` (that contains this README) and run one of
the following commands:

```bash
ipython notebook boston_housing.ipynb
```

or

```bash
jupyter notebook boston_housing.ipynb
```

This will open the Jupyter Notebook software and project file in your
browser.


https://www.python.org/download/releases/2.7/
