# Decision Trees and Random Forests in Python
This is a tutorial on tree model theory, including decision trees, boosting, bagging and random forests. 

Then we try to see an example usage of Decision Trees and Random Forests in python based on a data set of Kyphosis (a medical spine condition) patients. We want to predict whether of not a corrective spine surgery will be successful.

This data set includes the following:
* __Kyphosis__ is the target value that shows if the condition is absent or present after an operation.
* __Age__  is the age of the patients in months (which are children).
* __Number__ is the number of vertebrae involved.
* __Start__ is the starting vertebrae level of the surgery.

Note that for tree visualizations you should do the following:
* Install GraphViz: you can find the installation instructions ![here](http://www.graphviz.org/download/) (remember to add the _bin_ path to your PATH in system environment variables).
* You also need import the path in your notebook, as the method used for visualizing the tree needs to access the "dot.exe" executable: you can do this by:
`import os`
`os.environ["PATH"] += os.pathsep + 'C:/Program Files (x86)/Graphviz2.38/bin/'`
* Install Pydot: by `conda install pydot-ng` on Anaconda or using pip: `pip install pydot`.

The sources used to create this tutorial are the following:

  1.  Udemy's course Python for Data Science and Machine Learning Bootcamp.
  2.  The book An Introduction to Statistical Learning by Gareth James, Daniela Witten, Trevor Hastie and Robert Tibshirani.
