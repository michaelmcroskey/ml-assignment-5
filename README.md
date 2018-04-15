# ML Assignment 5
Michael McRoskey, Maggie Thomann

## Overview


## Files
1. **`question-1.ipynb`**:
2. **`question-2.ipynb`**:
3. data/
4. **`README.md`**
5. images/

## Usage
1. We recommend running in a virtual environment like [VirtualEnv](https://virtualenv.pypa.io/en/stable/)
2. Install dependencies with `$ pip install jupyter sklearn scipy pandas matplotlib graphviz`
3. Navigate to this repository in the terminal andexecute `$ jupyter notebook`. It should open a web browser.
4. You can then open `question-1.ipynb` or `question-2.ipynb` to view and execute code.


## Report


*Please provide a report that includes the error surface plot from Q1, and the results of the 10-fold CV analyses from Q2 as part of your submission. In addition, please provide the python code / notebook that was used to accomplish the assignment. Please upload to Sakai.*

### Question 1

Below is the Error Surface Plot from Q1.

![Alt text](images/q1.png?raw=true "Error Surface Plot from Q1")

Below is the Error Surface Plot from Q1 Extra Credit.

![Alt text](images/q1ec.png?raw=true "Error Surface Plot from Q1")

### Question 2

When running a t-test with error as the metric, the results are with a 95% confidence:

T_Test between MLPClassifier & DecisionTreeClassifier: T Value = -8.55448608048, P Value = 8.49922930944e-07
MLPClassifier is statistically significantly worse than DecisionTreeClassifier

When running a t-test with f-measure as the metric, the results are with a 95% confidence:

T_Test between MLPClassifier & DecisionTreeClassifier: T Value = -5.32803812636, P Value = 0.000203255046296
MLPClassifier is statistically significantly worse than DecisionTreeClassifier

The classifier performance is the same each time whether the scoring metric is the error as the metric or the f-measure.  