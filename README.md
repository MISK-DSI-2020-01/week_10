# Week 10 - Deep Learning continued, packages, SQL and wrap-up of course content

Welcome to week 10 of the Data Science Immersive course. Over the next week we'll wrap up Deep Learning by taking a look at computer vision. Then we'll look at one last essential on-the-job skill: SQL. We'll also look at creating functions and packages in Python and R. You may decide that your capstone project is an ideal testing groud to develop your own package.

## Deep Learning Material

The course material for Deep Learning can be found [here](https://github.com/misk-data-science/misk-dl). 

## Cloud Computing & Alternatives

Last week we set up an AWS AMI with a GPU and preinstalled RStudio Server and Tensorflow. We encountered two common issues: a mismatch in location or excess capacity for allotted instances. Both were easily solved, but took up to a day on Amazon's side. You can use this instance to prototype Deep Learning solutions (e.g. cloning our Deep Learning repository).

Unfortunately, it appears that there are some inconsistent bugs with getting computer vision to work well (i.e. Convnets, or CNNs) on the aforementioned instance. Thus, We'll use the class material to cover the concepts, see above) but for execution, we'll refer to two repositories of worked examples that accompany two popular books:

| Book | Author | Repository |
|-----|--------|-----------|
| [Deep Learning with Python](https://www.manning.com/books/deep-learning-with-python) | François Chollet, author of the Python Keras package | [GitHub](https://github.com/fchollet/deep-learning-with-python-notebooks)
| [Deep Learning with R](https://www.manning.com/books/deep-learning-with-r) | François Chollet & JJ Allaire, CEO of RStudio and author or the R port of the Keras package | [GitHub](https://github.com/jjallaire/deep-learning-with-r-notebooks)

These books mirror each other and make Deep Learning surprisingly understandable in your prefered language. 

If you want to use Python, the easiest way to access a GPU is via [Google Colab with GPU](https://colab.research.google.com/notebooks/gpu.ipynb). Alternatively, I have had success with [PaperSpace](https://www.paperspace.com/) in the past (although I haven't used them for a long time). They are inexpensive (but remember to shut off your machine!) and easy to get set up.

## Delivering Data Science Products via Packages

Developing a package for an existing or new workflow is a common and very useful deliverable for a data scientist. Thus, you may decide to use your Capstone Project as an opportunity to delivering your analysis in the form of a package.

You can find the course notes for package development [here](https://github.com/misk-data-science/misk-packages) and convenient package templates in Python and R [here](https://github.com/misk-data-science/package-template).

## Additional Materials for your Capstone Project

A reminder, for those of you intersted in exploring Natural Language Processing the course material can be found [here](http://scavetta.academy/misk/nlp/0_main.html).
