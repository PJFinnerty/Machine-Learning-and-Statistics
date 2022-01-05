# Machine-Learning-and-Statistics Assessmentc - Peter Finnerty

## Overview

***

This repository contains the assessment material for the Machine Learning and Statistics module, as part of the Higher Diploma in Science in Computing (Data Analytics). 

The primary motivation behind the project is to demonstrate understanding of core Machine Learning concepts, though practical examples. The Machine Learning libraries that will be used are SciKit-Learn and SciPy.Stats - both of which are libraries within the Python programming language, that the assessment is completed in.

There are two Jupyter notebooks in this assessment, 'SciKit-Learn.ipynb' and 'SciPy.Stats.ipynb'. 

1. SciKit Learn: The assessment requires the following in this notebook:
- An overview of the SciKit-Learn library. I have completed this using research from the SciKit-Learn documentation, various tutorials and articles and in particular, a video lecture from Andreas Mueller, a developer that has worked on the SciKit-learn library. These sources are available in the references.

- A demonstration of 3 SciKit-Learn algorithms. I have chosen to use the Red Wine Quality Dataset for this task. The three algorithms chosen are Simple Linear Regression, K-nearest Neighbor and RandomForest.

- A visualisation of these algorithms with neatly laid out plots. I have included Seaborn plots such as heatmaps, scatterplots and histograms.

2. SciPy.Stats: The assessments requires a notebook that contains material from Scipy's Stats module. This includes the following:

- An overview of the SciPy.Stats module, including demonstations and explanations of the distribution and statistical functions.

- A One Way Anova on an appropriate dataset. I have chosen to completed this part of the assessment using the 'Diet' dataset, which is designed to classify which Diet is most likely to lead to a drop in Body Mass Index. The 6 assumptions are first satisfied, following this the One-Way Anova is completed on the data.

- A visualisation using Seaborn plots is also required.

## Installation

***

The following softwares must be installed for this repository to work:
* Anaconda - this will ensure that you can run Python and it's built in libraries. For Windows installation, go to this link: https://docs.anaconda.com/anaconda/install/windows/ - this will also provide instructions for download.

* Jupyter Notebook - this is a web-based computing interface, for runing Python interactively. It is launched from the command line, by first going to the repository address and typing 'jupyter notebook'. This is conveniently downloaded as part of Anaconda, so no installation is necessary.

* Git - you will need to have the Git software running on your machine, in order to copy the machine from GitHub to your local machine. Git can be downloaded here: https://git-scm.com/downloads

* To clone this repository down to your machine, copy the Https URL available on the GitHub repository page and run the following commands in your command terminal:
<br>*clone git@github.com:PJFinnerty/Machine-Learning-and-Statistics.git*
- The repository will then be copied to your local machine current folder, and will not require a password.

- Enter the repository by typing:
<br>*cd Machine-Learning-and-Statistics*

- Open the notebook by typing:
<br>*jupyter notebook*

* Go to your browser, and a tab should have opened on a local host address (typically port 8888). You can traverse the repository files from the Jupyter interface, including the specific notebooks and this README file.

## File List
***
The following files are present in this repository:

1. SciKit-Learn.ipynb - Sklearn Jupyter notebook described above
2. SciPy.Stats.ipynb -  Jupyter notebook on Scipy.Stats module as described above
3. README - this file
4. Requirements.txt - the file that lists the python packages that you must have pip installed or imported
5. winequality-red.csv - the dataset that is used in the Sklearn notebook
6. Powerprodction.csv - another dataset used in the Sklearn overview section
7. Diet.csv - the dataset that a One-Way Anova is completed on in the SciPy.Stats notebook
8. diet_BMI_incl.csv - the same as above but with the BMI already calculated (for use in demonstration section of Sklearn notebook)
9. Licence - the MIT licence associated with this repository


## References
***
#### Articles
1. IBM, supervised-vs-unsupervised, https://www.ibm.com/cloud/blog/supervised-vs-unsupervised-learning

2. Machine Learning Mastery, Supervised Vs Unsupervised, https://machinelearningmastery.com/supervised-and-unsupervised-machine-learning-algorithms/

3. Machine Learning Masters, Clustering Algorithms, https://machinelearningmastery.com/clustering-algorithms-with-python/).

4. *Lecure from Andreas Mueller of Sklearn*, https://www.youtube.com/watch?v=juEOOQntrd0&t=1058s

5. Simplilearn, Scikit-Learn Tutorial, explanations on scaling, preprocessing and using RandomForest, https://www.youtube.com/watch?v=0Lt9w-BxKFQ&t=1659s

6. Scipy.stats documentation, https://www.great-esf.eu/AstroStats13-Python/numpy/scipystats.html

7. Sklearn documentation, https://scikit-learn.org/stable/

8. Continuous Distributions definition, Minitab, (https://support.minitab.com/en-us/minitab-express/1/help-and-how-to/basic-statistics/probability-distributions/supporting-topics/basics/continuous-and-discrete-probability-distributions/).

9. 'Four ways to do a one-way anova', Marsja, https://www.marsja.se/four-ways-to-conduct-one-way-anovas-using-python/

#### Images

1. Medium, Preproccesing steps, https://miro.medium.com/max/702/1*NfTkTp_35ylyDIdreYb9Sw.png

2. Medium, Clustering, https://miro.medium.com/max/1000/1*0DDt5Xp9z6ecj5eL6FNAfQ.png

3. Kdnuggets, Train, Test, and validated data, https://www.kdnuggets.com/wp-content/uploads/train_test_split.jpg

4. Medium, Dimensionality Reduction, https://miro.medium.com/max/959/1*kK4aMPHQ89ssFEus6RT4Yw.jpeg

5. Continuous Distribution image, Minitab, https://support.minitab.com/en-us/minitab-express/1/distribution_plot_normal_weight_shade_middle.xml_Graph_cmd1o1.png

6. Correlation function image, Qutip, https://qutip.org/docs/3.0.1/guide/scripts/correlation_ex1.hires.png

#### Solutions

1. Towards Data Science, Running KNN for various values of n_neighbors and storing results, https://towardsdatascience.com/k-nearest-neighbors-94395f445221

2. 'Incorrect Confusion Matrix', StackOverflow, https://stackoverflow.com/questions/57029115/incorrect-confusion-matrix-plot

3. 'Exloring the continuous distribution', Towards Data Science, https://towardsdatascience.com/exploring-normal-distribution-with-jupyter-notebook-3645ec2d83f8

