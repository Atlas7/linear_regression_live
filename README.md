# linear_regression_live
This is the code for the "How to Do Linear Regression the Right Way" live session by Siraj Raval on Youtube. I've merely wrap the project into an Anaconda / Conda environment for ease of collaboration.


## Overview

This is the code for [this](https://youtu.be/uwwWVAgJBcM) video on Youtube by Siraj Raval. I'm using a small dataset of student test scores and the amount of hours they studied. Intuitively, there must be a relationship right? The more you study, the better your test scores should be. We're going to use [linear regression](https://onlinecourses.science.psu.edu/stat501/node/250) to prove this relationship. 

Here are some helpful links:

#### Gradient descent visualization
https://raw.githubusercontent.com/mattnedrich/GradientDescentExample/master/gradient_descent_example.gif

#### Sum of squared distances formula (to calculate our error)
https://spin.atomicobject.com/wp-content/uploads/linear_regression_error1.png

#### Partial derivative with respect to b and m (to perform gradient descent)
https://spin.atomicobject.com/wp-content/uploads/linear_regression_gradient1.png


# Conda installation

git clone this repo.

Create the conda environment as per the `environment.yml` file - see dependencies and Python version there.


```
conda env create
```

Activate the conda environment:

```
source activate linear_regression_live
```

We are now in the same conda environment!

# Usage

Navigate into the repo.

Run the code

```
python demo.py
```

You should see the result print in the console.

```
Starting gradient descent at b = 0, m = 0, error = 5565.107834483211
Running...
After 1000 iterations b = 0.08893651993741346, m = 1.4777440851894448, error = 112.61481011613473
```

## Credits

Credits for this code go to:
- [mattnedrich](https://github.com/mattnedrich)
- [llSourcell](https://github.com/llSourcell).

I've merely adjusted the wrapper to get people started in Conda / Anaconda environment.
