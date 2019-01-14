Introduction to Machine learning (with Andreas Mueller)
========================================================


Instructor
-----------

- [Andreas Mueller](http://amuller.github.io) [@amuellerml](https://twitter.com/amuellerml) - Columbia University; [Book: Introduction to Machine Learning with Python](http://shop.oreilly.com/product/0636920030515.do)

---

This repository will contain the teaching material and other info associated
with the "Introduction to Machine Learning" course.

Content
-------

- [Introduction to ML](https://amueller.github.io/ml-training-intro/slides/00-introduction.html)
- [Supervised Learning](https://amueller.github.io/ml-training-intro/slides/01-supervised-learning.html)
- [Unsupervised Learning](https://amueller.github.io/ml-training-intro/slides/02-unsupervised-learning.html)
- [Cross-validation and Grid-Search](https://amueller.github.io/ml-training-intro/slides/03-cross-validation-grid-search.html)
- [Preprocessing](https://amueller.github.io/ml-training-intro/slides/04-preprocessing.html)
- [Linear Models for Regression](https://amueller.github.io/ml-training-intro/slides/05-linear-models-regression.html)
- [Linear Models for Classification](https://amueller.github.io/ml-training-intro/slides/06-linear-models-classification.html)
- [Trees and Forests](https://amueller.github.io/ml-training-intro/slides/07-trees-forests.html)
- [Gradient Boosted Trees](https://amueller.github.io/ml-training-intro/slides/08-gradient-boosting.html)



Obtaining the Tutorial Material
--------------------------------


If you are familiar with git, it is probably most convenient if you clone the GitHub repository. This
is highly encouraged as it allows you to easily synchronize any changes to the material.

```
git clone https://github.com/amueller/ml-training-intro.git
```

If you are not familiar with git, you can download the repository as a .zip file by heading over to the GitHub repository (https://github.com/amueller/ml-training-intro) in your browser and click the green “Download” button in the upper right.

![](images/download-repo.png)

Please note that I may add and improve the material until shortly before the tutorial session, and we recommend you to update your copy of the materials one day before the tutorials. If you have an GitHub account and forked/cloned the repository via GitHub, you can sync your existing fork with via the following commands:

```
git pull origin master
```


Installation Notes
------------------

This tutorial will require recent installations of

- [NumPy](http://www.numpy.org)
- [SciPy](http://www.scipy.org)
- [matplotlib](http://matplotlib.org)
- [pillow](https://python-pillow.org)
- [pandas](http://pandas.pydata.org)
- [scikit-learn](http://scikit-learn.org/stable/) (>=0.18.1)
- [IPython](http://ipython.readthedocs.org/en/stable/)
- [Jupyter Notebook](http://jupyter.org)

The last one is important, you should be able to type:

    jupyter notebook

in your terminal window and see the notebook panel load in your web browser.
Try opening and running a notebook from the material to see check that it works.

For users who do not yet have these  packages installed, a relatively
painless way to install all the requirements is to use a Python distribution
such as [Anaconda](https://www.continuum.io/downloads), which includes
the most relevant Python packages for science, math, engineering, and
data analysis; Anaconda can be downloaded and installed for free
including commercial use and redistribution.
The code examples in this tutorial should be compatible to Python 2.7,
Python 3.4 and later. However, it's recommended to use a recent Python version (like
3.5 or 3.6).

After obtaining the material, we **strongly recommend** you to open and execute
a Jupyter Notebook `jupter notebook check_env.ipynb` that is located at the
top level of this repository. Inside the repository, you can open the notebook
by executing

```bash
jupyter notebook check_env.ipynb
```

inside this repository. Inside the Notebook, you can run the code cell by
clicking on the "Run Cells" button as illustrated in the figure below:

![](images/check_env-1.png)


Finally, if your environment satisfies the requirements for the tutorials, the executed code cell will produce an output message as shown below:

![](images/check_env-2.png)
