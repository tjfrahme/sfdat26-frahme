## SF DAT 26 Course Repository

Course materials for General Assembly's Data Science course in San Francisco, CA (8/10/16 - 10/19/16).

**Instructors:** [Sinan Ozdemir](https://www.linkedin.com/in/sinan-ozdemir-10568534) 
**Teaching Assistants:**
[Peter Gao](https://www.linkedin.com/in/peterhgao) / [Cari Levay](https://www.linkedin.com/in/carilevay)

**Course Times**

Monday/Wednesday: 6:30pm - 9:30pm

**Office hours:** 

TBD

All courses / office hours will be held in the student center at GA, 225 Bush Street

**[Course Project Information](project.md)**

**[Course Project Examples](project-examples.md)**


Monday | Wednesday | Project Milestone | HW
--- | --- | --- | ---
No Class | 8/10: Introduction / Expectations / Intro to Data Science
8/15: Pandas | 8/17: APIs / Web Scraping 101 | | HW 1 Assigned (W)
8/22: Intro to Machine Learning / KNN | 8/24: Linear Regression / Model Evaluation | Three Potential Project Ideas (W) | 
8/29: Model Evaluation Con't / Logistic Regression | 8/31:  / Natural Language Processing ||HW 1 Due (W)
9/5: Labor Day (No Class) | 9/7: Naive Bayes Classification || 
9/12: Advanced Sklearn (Pipeline and Feaure Unions) | 9/14: Review | |HW 2 Assigned (W)
9/19: Decision Trees | 9/21: Ensembling Techniques | First Draft Due (W) | 
9/26: Dimension Reduction | 9/28: Clustering / Topic Modelling | Peer Review Due (M)
10/3: Stochastic Gradient Descent | 10/5: Neural Networks / Deep Learning | |HW 2 Due (W)
10/10: Recommendation Engines | 10/12: Web Development with Flask | |
10/17: Data Science in Practice / Projects | 10/19: Projects | Git Er Done | Git Er Done


### Installation and Setup
* Install the [Anaconda distribution](http://continuum.io/downloads) of Python 2.7x.
* Setup a [conda virtual environment](https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/20/conda/)
* Install [Git](http://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and create a [GitHub](https://github.com/) account.
* Once you receive an email invitation from [Slack](https://slack.com/), join our "SFDAT26 team" and add your photo!

### Resources
* [PEP 8 - Style Guide for Python](http://www.python.org/dev/peps/pep-0008)
* [Learn How to Think Like a Computer Scientist](http://interactivepython.org/runestone/static/thinkcspy/toc.html#t-o-c)
* Potential book for course? [:)](https://www.amazon.com/Principles-Data-Science-Sinan-Ozdemir-ebook/dp/B01A8T8YNC)


##Introduction / Expectations / Intro to Data Science

Agenda

* Introduction to General Assembly [slides](slides/01_DAT_intro_deck.pdf)
* Course overview: our philosophy and expectations ([slides](slides/01_course_overview.pdf))
* Ice Breaker

Break -- [**Command Line Tutorial**](http://generalassembly.github.io/prework/cl)

* Figure out office hours
* Intro to Data Science: [slides](slides/01_intro_to_data_science.pdf)

Homework


* Setup a [conda virtual environment](https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/20/conda/)
* Install [Git](http://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and create a [GitHub](https://github.com/) account.
	* Read my intro to [Git](slides/01_git.pdf) and be sure to come back on monday with your very own repository called "sfdat26-lastname"
* Once you receive an email invitation from [Slack](https://slack.com/), join our "SFDAT26 team" and add your photo!
* Introduction on how to read and write iPython notebooks [tutorial](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat22/blob/master/notebooks/intro_to_ipython_notebooks.ipynb)


### Class 2: Introduction to Pandas

####Goals

* Feel comfortable importing, manipulating, and graphing data using Python's Pandas
* Be able to find missing values and begin to have a sense of how to deal with them


####Agenda

* Don't forget to `git pull` in the sfdat26 repo in your command line
* Intro to Pandas walkthrough [here](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat26/blob/master/notebooks/02_pandas.ipynb)
	* [Pandas Lab 2](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat26/blob/master/labs/02_pandas_lab.ipynb)

####Homework
* Go through the python class/lab work and finish any exercise you weren't able to in class
* Make sure you have all of the repos cloned and ready to go
	* You should have both "sfdat26" and "sfdat26_work"
* Read Greg Reda's [Intro to Pandas](http://www.gregreda.com/2013/10/26/intro-to-pandas-data-structures/)
* Take a look at Kaggle's [Titanic competition](https://www.kaggle.com/c/titanic)
* I will be using a module called `tweepy` next time. 
	* To install please type into your console `conda install tweepy` 
		* OR if that does not work, `pip install tweepy`

#### Resources:
* Another Git tutorial [here](http://try.github.io)
* In depth Git/Github tutorial series made by a GA_DC  Data Science Instructor [here](https://www.youtube.com/playlist?list=PL5-da3qGB5IBLMp7LtN8Nc3Efd4hJq0kD)
* [Another Intro to Pandas](http://nbviewer.ipython.org/gist/wesm/4757075/PandasTour.ipynb) (Written by Wes McKinney and is adapted from his book)
	* [Here](https://vimeo.com/59324550) is a video of Wes McKinney going through his ipython notebook!
* Examples of [joins in Pandas](http://www.gregreda.com/2013/10/26/working-with-pandas-dataframes/#joining)
* For more on Pandas plotting, read the [visualization page](http://pandas.pydata.org/pandas-docs/stable/visualization.html) from the official Pandas documentation.

#### Next Time on SFDAT26...

* Maria finds out that Sancho has been cheating on her with her.. mother!
* We will use python to programatically obtain data via open sources on the internet
	* We will be scraping the [National UFO reporting center](http://nuforc.org/)
	* We will be collecting tweets regarding Donald Trump and Hilary Clinton
	* We will be examining What people are really looking for in a data scientist..
	
* We will continue to use pandas to investigate missing values in data and have a sense of how to deal with them


### Class 3: APIs / Web Scraping 101

####Agenda

* To install tweepy please type into your console `conda install tweepy` 
	* OR if that does not work, `pip install tweepy`
* Slides on Getting Data [here](slides/03_getting_data.pdf)
* Intro to Regular Expressions [here](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat26/blob/master/notebooks/03_regex_example.ipynb)
* Getting Data from the open web [here](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat26/blob/master/notebooks/03_getting_data_from_web.ipynb)
* Getting Data from an API [here](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat26/blob/master/notebooks/03_getting_data_from_api.ipynb)
* LAB on getting data [here](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat26/blob/master/labs/03_getting_data_lab.ipynb)

####Homework
* The first homework will be assigned by tomorrow morning (in a homework folder) and it is due in two Wednesdays (8/31)
	* It is a combo of pandas question with a bit of API/scraping
	* Please push your completed work to your sfdat26_work repo for grading
* Your [first project milestone](project.md) is due next Wednesday. It is the first three ideas you have for your project. Think about potential interesting sources of data you would like to work with. This can come from work, hobby, or elsewhere!

####Resources:

* [Mashape](https://www.mashape.com/) allows you to explore tons of different APIs. Alternatively, a Python API wrapper is available for many popular APIs.
* [The Data Science Toolkit](http://www.datasciencetoolkit.org/) is a collection of location-based and text-related APIs.
* [API Integration in Python](https://realpython.com/blog/python/api-integration-in-python/) provides a very readable introduction to REST APIs.
* [Microsoft's Face Detection API](https://www.microsoft.com/cognitive-services/en-us/face-api#detection), which powers [How-Old.net](https://how-old.net/), is a great example of how a machine learning API can be leveraged to produce a compelling web application.
Web Scraping Resources:
* For a much longer web scraping tutorial covering Beautiful Soup, lxml, XPath, and Selenium, watch [Web Scraping with Python](https://www.youtube.com/watch?v=p1iX0uxM1w8) (3 hours 23 minutes) from PyCon 2014. The slides and code are also available.
* [import.io](https://www.import.io/) and [Kimono](https://www.kimonolabs.com/) claim to allow you to scrape websites without writing any code. Its alrighhhtttttt
* [How a Math Genius Hacked OkCupid](http://www.wired.com/2014/01/how-to-hack-okcupid/all/) to Find True Love and [How Netflix Reverse Engineered](http://www.theatlantic.com/technology/archive/2014/01/how-netflix-reverse-engineered-hollywood/282679/?single_page=true) Hollywood are two fun examples of how web scraping has been used to build interesting datasets.

### Class 4: Intro to Machine Learning / KNN

####Agenda

* Iris pre-work [code](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat26/blob/master/notebooks/04_iris_prework.ipynb)
	* Using numpy to investigate the iris dataset further
	* Understanding how humans learn so that we can teach the machine!
	* If nedded, read intro to numpy [code](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat26/blob/master/notebooks/04_numpy_ref.ipynb)
		* Numerical Python, code adapted from tutorial [here](http://www.engr.ucsb.edu/~shell/che210d/numpy.pdf)
		* Special attention to the idea of the np.array

* Intro to Machine Learning and KNN [slides](slides/04_ml_knn.pdf)
	* Supervised vs Unsupervised Learning
	* Regression vs. Classification

* [Lab](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat26/blob/master/labs/04_knn_lab.ipynb) to use KNN models to investigate accelerometer data


####Homework

* The one page project milestone as well as the pandas homework! [See requirements here](project.md)
* Read this excellent article, [Understanding the Bias-Variance Tradeoff](http://scott.fortmann-roe.com/docs/BiasVariance.html), and be prepared to discuss it in class on Wednesday. (You can ignore sections 4.2 and 4.3.) Here are some questions to think about while you read:
    * In the Party Registration example, what are the features? What is the response? Is this a regression or classification problem?
    * In the interactive visualization, try using different values for K across different sets of training data. What value of K do you think is "best"? How do you define "best"?
    * In the visualization, what do the lighter colors versus the darker colors mean? How is the darkness calculated?
    * How does the choice of K affect model bias? How about variance?
    * As you experiment with K and generate new training data, how can you "see" high versus low variance? How can you "see" high versus low bias?
    * Why should we care about variance at all? Shouldn't we just minimize bias and ignore variance?
    * Does a high value for K cause over-fitting or under-fitting?
* For our talk on linear regression, read:
	* This [explanation](http://blog.minitab.com/blog/adventures-in-statistics/how-to-correctly-interpret-p-values) of p values
	* [Correlation does not imply Causation](http://tylervigen.com/spurious-correlations)
	* [P-values can't always be trusted](http://fivethirtyeight.com/features/science-isnt-broken/#part2)
	
    
**Resources:**

* For a more in-depth look at machine learning, read section 2.1 (14 pages) of Hastie and Tibshirani's excellent book, [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/). (It's a free PDF download!)
* Stackoverflow article on the difference between generative and discriminative models [here](http://stackoverflow.com/questions/879432/what-is-the-difference-between-a-generative-and-discriminative-algorithm)




### Class 5: Model Evaluation Procedures / Linear Regression

**Agenda**

* Discusss with people at your table about your three potential ideas.
	* Try to figure out which kinds of machine learning would be appropiate
		* supervised
		* unsupervised
* Model evaluation procedures ([slides](slides/05_model_evaluation_procedures.pdf), [code](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat26/blob/master/notebooks/05_model_evaluation.ipynb))
* Linear regression ([notebook](http://nbviewer.ipython.org/github/sinanuozdemir/sfdat26/blob/master/notebooks/05_linear_regression.ipynb))
	* To run this, I use a module called "seaborn" 
	* To install to anywhere in your terminal (git bash) and type in `sudo pip install seaborn`
	* In depth slides [here](slides/05_linear_regression.pdf)
* LAB -- Yelp dataset [here](labs/05_yelp_reviews.md) with the [Yelp reviews data](data/yelp.csv). It is not required but your next homework will involve this dataset so it would be helpful to take a look now!
* Discuss the [article](http://scott.fortmann-roe.com/docs/BiasVariance.html) on the bias-variance tradeoff
* Look as some [code](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat26/blob/master/notebooks/05_bias_variance_tradeoff.ipynb) on the bias variace tradeoff
	


**Homework:**

* Please upload your three potential ideas for your final project to your personal sfdat26_work repo
	* [Here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) is a markdown cheatsheet for making your very own markdown files
	* I recommend [Macdown](http://macdown.uranusjr.com/) editor for mac users and [MarkPad](http://code52.org/DownmarkerWPF/) for windows users
* Watch these videos on [probability](https://www.youtube.com/watch?v=o4QmoNfW3bI) and [odds](https://www.youtube.com/watch?v=GxbXQjX7fC0) (8 minutes) if you're not familiar with either of those terms.
* Read these excellent articles from BetterExplained: [An Intuitive Guide To Exponential Functions & e](http://betterexplained.com/articles/an-intuitive-guide-to-exponential-functions-e/) and [Demystifying the Natural Logarithm (ln)](http://betterexplained.com/articles/demystifying-the-natural-logarithm-ln/).
* [Homework 1](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat26/blob/master/hw/hw1.ipynb) is due in **7 days**!

**Resources:**

* [Correlation does not imply Causation](http://tylervigen.com/spurious-correlations)
* [P-values can't always be trusted](http://fivethirtyeight.com/features/science-isnt-broken/#part2)
* Setosa has an excellent [interactive visualization](http://setosa.io/ev/ordinary-least-squares-regression/) of linear regression.
* To go much more in-depth on linear regression, read Chapter 3 of [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/), from which this lesson was adapted. Alternatively, watch the [related videos](http://www.dataschool.io/15-hours-of-expert-machine-learning-videos/) or read my [quick reference guide](http://www.dataschool.io/applying-and-interpreting-linear-regression/) to the key points in that chapter.
* To learn more about Statsmodels and how to interpret the output, DataRobot has some decent posts on [simple linear regression](http://www.datarobot.com/blog/ordinary-least-squares-in-python/) and [multiple linear regression](http://www.datarobot.com/blog/multiple-regression-using-statsmodels/).
* This [introduction to linear regression](http://people.duke.edu/~rnau/regintro.htm) is much more detailed and mathematically thorough, and includes lots of good advice.
* This is a relatively quick post on the [assumptions of linear regression](http://pareonline.net/getvn.asp?n=2&v=8).
* John Rauser's talk on [Statistics Without the Agonizing Pain](https://www.youtube.com/watch?v=5Dnw46eC-0o) (12 minutes) gives a great explanation of how the null hypothesis is rejected.
* A major scientific journal recently banned the use of p-values:
    * Scientific American has a nice [summary](http://www.scientificamerican.com/article/scientists-perturbed-by-loss-of-stat-tools-to-sift-research-fudge-from-fact/) of the ban.
    * This [response](http://www.nature.com/news/statistics-p-values-are-just-the-tip-of-the-iceberg-1.17412) to the ban in Nature argues that "decisions that are made earlier in data analysis have a much greater impact on results".
    * Andrew Gelman has a readable [paper](http://www.stat.columbia.edu/~gelman/research/unpublished/p_hacking.pdf) in which he argues that "it's easy to find a p < .05 comparison even if nothing is going on, if you look hard enough".
* An article on ["P Hacking"](http://www.dailydot.com/geek/data-manipulation-tool-science-p-hacking/) the idea that you can alter data in order to achieve good p values
* Here's a great [30-second explanation of overfitting](http://www.quora.com/What-is-an-intuitive-explanation-of-overfitting/answer/Jessica-Su).
* For more on today's topics, these videos from Hastie and Tibshirani are useful: [overfitting and train/test split](https://www.youtube.com/watch?v=_2ij6eaaSl0) (14 minutes), [cross-validation](https://www.youtube.com/watch?v=nZAM5OXrktY) (14 minutes). (Note that they use the terminology "validation set" instead of "test set".)
    * Alternatively, read section 5.1 (12 pages) of [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/), which covers the same content as the videos.
* This video from Caltech's machine learning course presents an [excellent, simple example of the bias-variance tradeoff](http://work.caltech.edu/library/081.html) (15 minutes) that may help you to visualize bias and variance.


### Class 6: Logistic Regression
* Linear regression (Continued) [notebook](http://nbviewer.ipython.org/github/sinanuozdemir/sfdat26/blob/master/notebooks/05_linear_regression.ipynb)
* Logistic regression [notebook](http://nbviewer.ipython.org/github/sinanuozdemir/sfdat26/blob/master/notebooks/06_logistic_regression.ipynb) and [slides](slides/06_logistic_regression.pdf) 
	* Confusion matrix [slides](slides/06_confusion_matrix.pdf)
* LAB -- Exercise with Titanic data [instructions](labs/06_titanic.md)

**Homework:**

* Homework due in **2 days!!!!**

* If you aren't yet comfortable with all of the confusion matrix terminology, watch Rahul Patwari's videos on [Intuitive sensitivity and specificity](https://www.youtube.com/watch?v=U4_3fditnWg) (9 minutes) and [The tradeoff between sensitivity and specificity](https://www.youtube.com/watch?v=vtYDyGGeQyo) (13 minutes).

**Resources:**

* To go deeper into logistic regression, read the first three sections of Chapter 4 of [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/), or watch the [first three videos](http://www.dataschool.io/15-hours-of-expert-machine-learning-videos/) (30 minutes) from that chapter.
* For a math-ier explanation of logistic regression, watch the first seven videos (71 minutes) from week 3 of Andrew Ng's [machine learning course](https://www.coursera.org/learn/machine-learning/home/info), or read the [related lecture notes](http://www.holehouse.org/mlclass/06_Logistic_Regression.html) compiled by a student.
* For more on interpreting logistic regression coefficients, read this excellent [guide](http://www.ats.ucla.edu/stat/mult_pkg/faq/general/odds_ratio.htm) by UCLA's IDRE and these [lecture notes](http://www.unm.edu/~schrader/biostat/bio2/Spr06/lec11.pdf) from the University of New Mexico.
* The scikit-learn documentation has a nice [explanation](http://scikit-learn.org/stable/modules/calibration.html) of what it means for a predicted probability to be calibrated.
* [Supervised learning superstitions cheat sheet](http://ryancompton.net/assets/ml_cheat_sheet/supervised_learning.html) is a very nice comparison of four classifiers we cover in the course (logistic regression, decision trees, KNN, Naive Bayes) and one classifier we do not cover (Support Vector Machines).
* This [simple guide to confusion matrix terminology](http://www.dataschool.io/simple-guide-to-confusion-matrix-terminology/) may be useful to you as a reference.


##Class 7: Natural Language Processing


**pre-work**

* Download all of the NLTK collections.
   * In Python, use the following commands to bring up the download menu.
   * ```import nltk```
   * ```nltk.download()```
   * Choose "all".
   * Alternatively, just type ```nltk.download('all')```
* Install three new packages: ```yahoo_finance```,  ```textblob``` and ```lda```.
   * Open a terminal or command prompt.
   * Type ```pip install yahoo_finance``` ```pip install textblob``` and ```pip install lda```.
 


**Agenda**

* Quick recap of what we've done so far
* Naural Language Processing is the science of turning words and sentences into data and numbers. Today we will be exploring techniques into this field
* [code](notebooks/07_nlp.ipynb) showing topics in NLP
* [lab](labs/07_nlp_lab.ipynb) analyzing tweets about the stock market
* NO CLASS ON MONDAY


**Homework:**

* Read Paul Graham's [A Plan for Spam](http://www.paulgraham.com/spam.html) and be prepared to **discuss it in class when we get back!**. Here are some questions to think about while you read:
    * Should a spam filter optimize for sensitivity or specificity, in Paul's opinion?
    * Before he tried the "statistical approach" to spam filtering, what was his approach?
    * How exactly does his statistical filtering system work?
    * What did Paul say were some of the benefits of the statistical approach?
    * How good was his prediction of the "spam of the future"?
* Below are the foundational topics upon which Wednesday's class will depend. Please review these materials before class:
    * **Confusion matrix:** [a good guide](http://www.dataschool.io/simple-guide-to-confusion-matrix-terminology/) roughly mirrors the lecture from class 10.
    * **Sensitivity and specificity:** Rahul Patwari has an [excellent video](https://www.youtube.com/watch?v=U4_3fditnWg&list=PL41ckbAGB5S2PavLIXUETzAmi5reIod23) (9 minutes).
    * **Basics of probability:** These [introductory slides](https://docs.google.com/presentation/d/1cM2dVbJgTWMkHoVNmYlB9df6P2H8BrjaqAcZTaLe9dA/edit#slide=id.gfc3caad2_00) (from the [OpenIntro Statistics textbook](https://www.openintro.org/stat/textbook.php)) are quite good and include integrated quizzes. Pay specific attention to these terms: probability, sample space, mutually exclusive, independent.


##Class 8: Naive Bayes Classifier

Today we are going over advanced metrics for classification models and learning a brand new classification model called naive bayes!

**Agenda**

* Are you smart enough to work at [Facebook?](https://www.glassdoor.com/Interview/You-re-about-to-get-on-a-plane-to-Seattle-You-want-to-know-if-you-should-bring-an-umbrella-You-call-3-random-friends-of-y-QTN_519262.htm)
* Learn about Naive Bayes and ROC/AUC curves 
	* 	Slides [here](slides/08_naive_bayes_roc_auc.pdf)
	* 	Code [here](notebooks/08_naive_bayes_roc_auc.ipynb)
	* In the code file above we will create our own spam classifier!
* Work on Homework / previous labs


**Resources**

* Bayes Theorem as applied to Monty Hall [here](https://www.quora.com/How-do-I-solve-the-Monty-Hall-Problem-using-Bayes-Theorem) and [here](http://angrystatistician.blogspot.com/2012/06/bayes-solution-to-monty-hall.html)
* Video on [ROC Curves](https://www.youtube.com/watch?v=21Igj5Pr6u4&list=PL41ckbAGB5S2PavLIXUETzAmi5reIod23) (12 minutes).
* My good buddy's [blog post about the ROC video](http://www.dataschool.io/roc-curves-and-auc-explained/) includes the complete transcript and screenshots, in case you learn better by reading instead of watching.
* Accuracy vs AUC discussions [here](http://stats.stackexchange.com/questions/32139/roc-vs-accuracy) and [here](http://datascience.stackexchange.com/questions/806/advantages-of-auc-vs-standard-accuracy)





##Class 9: Advanced Sklearn Modules

**Agenda**

Today we are going to talk about four major things as related to advanced sklearn features and modules:

* We will use sklearn's [Pipeline](http://scikit-learn.org/stable/modules/generated/sklearn.pipeline.Pipeline.html) feature to chain together multiple sklearn modules
* We will look at the [Feature Selection](http://scikit-learn.org/stable/modules/feature_selection.html) module to automatically find the most effective features in our dataset
* We can use [Feature Unions](http://scikit-learn.org/stable/modules/generated/sklearn.pipeline.FeatureUnion.html) to combine several feature extraction techniques
* More on [StandardScalar](http://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html) as well
* Find the notebook [here](notebooks/09_advanced_sklearn.ipynb)!


### Class 10: Review (crime doesn't pay)
* Review on the board
* Review part deux ([notebook](http://nbviewer.ipython.org/github/sinanuozdemir/sfdat26/blob/master/notebooks/10_review.ipynb))
* LAB -- Kaggle competition [instructions](https://www.kaggle.com/c/sf-crime)

### Class 11: Decision Trees / Ensembling

* Decision trees ([notebook](notebooks/11_decision_trees.ipynb))
	* Bonus content deals with the algorithm behind building trees


** Homework **
* HW2 is live in the homework file
* Project milestone 2 is due on Wednesday!

**Resources:**

* scikit-learn's documentation on [decision trees](http://scikit-learn.org/stable/modules/tree.html) includes a nice overview of trees as well as tips for proper usage.
* For a more thorough introduction to decision trees, read section 4.3 (23 pages) of [Introduction to Data Mining](http://www-users.cs.umn.edu/~kumar/dmbook/index.php). (Chapter 4 is available as a free download.)
* If you want to go deep into the different decision tree algorithms, this slide deck contains [A Brief History of Classification and Regression Trees](https://drive.google.com/file/d/0B-BKohKl-jUYQ3RpMEF0OGRUU3RHVGpHY203NFd3Z19Nc1ZF/view).
* [The Science of Singing Along](http://www.doc.gold.ac.uk/~mas03dm/papers/PawleyMullensiefen_Singalong_2012.pdf) contains a neat regression tree (page 136) for predicting the percentage of an audience at a music venue that will sing along to a pop song.
* Decision trees are common in the medical field for differential diagnosis, such as this classification tree for [identifying psychosis](http://www.psychcongress.com/sites/naccme.com/files/images/pcn/saundras/psychosis_decision_tree.pdf).


### CLass 12: Ensembling Techniques

#### Agenda:
* Ensembling ([notebook](notebooks/12_ensembling.ipynb))
    * [Major League Baseball player data](data/hitters.csv) from 1986-87
    * [Data dictionary](https://cran.r-project.org/web/packages/ISLR/ISLR.pdf) (page 7)

#### Resources:
* scikit-learn's documentation on [ensemble methods](http://scikit-learn.org/stable/modules/ensemble.html) covers both "averaging methods" (such as bagging and Random Forests) as well as "boosting methods" (such as AdaBoost and Gradient Tree Boosting).
* MLWave's [Kaggle Ensembling Guide](http://mlwave.com/kaggle-ensembling-guide/) is very thorough and shows the many different ways that ensembling can take place.
* Browse the excellent [solution paper](https://docs.google.com/viewer?url=https://raw.githubusercontent.com/ChenglongChen/Kaggle_CrowdFlower/master/Doc/Kaggle_CrowdFlower_ChenglongChen.pdf) from the winner of Kaggle's [CrowdFlower competition](https://www.kaggle.com/c/crowdflower-search-relevance) for an example of the work and insight required to win a Kaggle competition.
* [Interpretable vs Powerful Predictive Models: Why We Need Them Both](https://medium.com/@chris_bour/interpretable-vs-powerful-predictive-models-why-we-need-them-both-990340074979) is a short post on how the tactics useful in a Kaggle competition are not always useful in the real world.
* [Not Even the People Who Write Algorithms Really Know How They Work](http://www.theatlantic.com/technology/archive/2015/09/not-even-the-people-who-write-algorithms-really-know-how-they-work/406099/) argues that the decreased interpretability of state-of-the-art machine learning models has a negative impact on society.
* For an intuitive explanation of Random Forests, read Edwin Chen's answer to [How do random forests work in layman's terms?](http://www.quora.com/Random-Forests/How-do-random-forests-work-in-laymans-terms/answer/Edwin-Chen-1)
* [Large Scale Decision Forests: Lessons Learned](http://blog.siftscience.com/blog/2015/large-scale-decision-forests-lessons-learned) is an excellent post from Sift Science about their custom implementation of Random Forests.
* [Unboxing the Random Forest Classifier](http://nerds.airbnb.com/unboxing-the-random-forest-classifier/) describes a way to interpret the inner workings of Random Forests beyond just feature importances.
* [Understanding Random Forests: From Theory to Practice](http://arxiv.org/pdf/1407.7502v3.pdf) is an in-depth academic analysis of Random Forests, including details of its implementation in scikit-learn.


### Class 13: Dimension Reduction

#### Agenda

* PCA
	* [Explained visually](http://setosa.io/ev/principal-component-analysis/)
    * [Slides](slides/13_dimension_reduction.pdf)
    * Code: [PCA](notebooks/13_pca.ipynb)

#### Resources
* Facial Recognition using [PCA](http://scikit-learn.org/stable/tutorial/statistical_inference/putting_together.html)
* Layman's intro to [PCA](https://www.youtube.com/watch?v=BfTMmoDFXyE)
* Simple PCA using [iris](http://sebastianraschka.com/Articles/2015_pca_in_3_steps.html)
* PCA step by step in [python](http://sebastianraschka.com/Articles/2014_pca_step_by_step.html)
* [Sklearn](http://scikit-learn.org/stable/modules/decomposition.html) page on dimension reduction techniques including SVD


### Class 14: Clustering / Topic Modelling
* Clustering ([slides](slides/14_clustering.pdf), [notebook](notebooks/14_clustering.ipynb))
    * K-means: [documentation](http://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html), [visualization 1](http://tech.nitoyon.com/en/blog/2013/11/07/k-means/), [visualization 2](http://www.naftaliharris.com/blog/visualizing-k-means-clustering/)
    * DBSCAN: [documentation](http://scikit-learn.org/stable/modules/generated/sklearn.cluster.DBSCAN.html), [visualization](http://www.naftaliharris.com/blog/visualizing-dbscan-clustering/)
    * LAB -- Pandora [notebook](labs/14_clustering_lab.ipynb)

**Homework:**

* **Homework 2 is due in one week!**

#### Resources
* [The Psychology Of Trump’s Twitter Followers](http://www.receptiviti.ai/blog/trumps-twitter-followers/)
* Sklearn clustering example [here](http://scikit-learn.org/stable/auto_examples/text/document_clustering.html) and [here](http://scikit-learn.org/0.15/auto_examples/document_clustering.html)
* LDA [explained](https://rstudio-pubs-static.s3.amazonaws.com/79360_850b2a69980c4488b1db95987a24867a.html)
* LSA [tutorial](http://mccormickml.com/2016/03/25/lsa-for-text-classification-tutorial/)

### Class 15: Stochastic Gradient Descent

**Agenda**

* Understand how vecotr calculus can help us minimize errors in our machine learning algorithms
* See how batch and stochastic gradient descent are effective tools
* notebook [here](notebooks/15_sgd.ipynb)

**Resources**

* Tutorial on gradient descent [here](http://machinelearningmastery.com/gradient-descent-for-machine-learning/)
* Another one [here](https://spin.atomicobject.com/2014/06/24/gradient-descent-linear-regression/)


**Homework**

* Homework 2 is due on Wednesday!!!!
* Install [Tensorflow](https://www.tensorflow.org/versions/r0.11/get_started/os_setup.html#anaconda-installation) and [skflow](https://github.com/tensorflow/skflow)
* After you have installed tensorflow, read this [intro to tensorflow](https://www.tensorflow.org/versions/r0.11/tutorials/mnist/beginners/index.html)


### Class 16: Deep Learning / Neural Networks

**Agenda**

* Understand what is meant by deep learning
* See how Tensorflow utilizes deep learning in thei neural networks
* Slides [here](slides/16_deep_nn.pdf)
* notebook [here](notebooks/16_deep_learning.ipynb)


**Resources**

* Blog [post](https://medium.com/ilenze-com/object-detection-using-deep-learning-for-advanced-users-part-1-183bbbb08b19#.u53gezr8l) on Object Detection
* Beginner [tutorial](https://www.tensorflow.org/versions/r0.9/tutorials/mnist/beginners/index.html) for tensorflow
* Directory of training in [Tensorflow](https://www.tensorflow.org/versions/r0.11/api_docs/python/train.html)

### Class 17: Recommendation Engines

**Agenda**

* See how companies like Pandora, Spotify, and Netflix make their recommendations
* Slides [here](slides/17_recommendation_engines.pdf)
* notebook [here](notebooks/17_recommenders.ipynb)


**Resources**

* Website on [The Netflix Prize](http://www.netflixprize.com/)
* Another [intro to recommendation engines](https://www.analyticsvidhya.com/blog/2016/06/quick-guide-build-recommendation-engine-python/)
* Using Kmeans to [make clusters for recommending](http://blogs.gartner.com/martin-kihn/how-to-build-a-recommender-system-in-python/)

### Class 18: Web Development with Flask and Heroku

**Objectives**

* To launch your own machine learning powered website

**Agenda**

* Sign up for a spot next week! [signups](https://docs.google.com/spreadsheets/d/1lGEQ6p3s7o6P2n2QhGZaH0ujrIhabh6Z7-vwYILn32Q/edit#gid=0)
* Present our speaker on Monday
* Tips on presentation
	* Start with [why](http://www.presentationzen.com/presentationzen/2010/05/the-importance-of-starting-from-why.html)

* Understand Web Development and how we can deploy machine learning models to the web using Flask and Heroku
* Slides [here](slides/18_web_development.pdf)

**Homework**

* Work on your project!!
* Work on your project!!
* Work on your project!!
* Work on your project!!
* please
* Work on your project!!




### Next Steps

The hardest thing to do now is to stay sharp! I have a few recommendations on next steps in order to make sure that you don't forget what we learned here! ![](https://s-media-cache-ak0.pinimg.com/originals/88/74/9d/88749d9e7fb7ef330b5e0b4ceb781cfd.jpg)

* Read [my book] (https://www.amazon.com/Principles-Data-Science-Sinan-Ozdemir-ebook/dp/B01A8T8YNC) ;)
* Always stay up to date on [Kaggle](http://kaggle.com)
	* Try working with some other people in this class!
	* Our Slack channel will stay around if you still want to post cool blogs, videos, etc!
* Try implementing some of the models we learned in class on your own!
	* Great book [Data Science From Scratch] (http://file.allitebooks.com/20150707/Data%20Science%20from%20Scratch-%20First%20Principles%20with%20Python.pdf) with [code](https://github.com/joelgrus/data-science-from-scratch)

	*  Text classification with Naive Bayes from Scratch [here] (https://web.stanford.edu/class/cs124/lec/naivebayes.pdf)
	*  Introduction to Statistical Learning [book](http://www-bcf.usc.edu/~gareth/ISL/) Videos [here](http://www.dataschool.io/15-hours-of-expert-machine-learning-videos/)
	*  PCA by hand [here](http://sebastianraschka.com/Articles/2014_pca_step_by_step.html)
* Take a look at the **Resources** for each class to get a deeper understanding of what we've learned. Trust me there are a lot
* Follow data scientists on Twitter.  This will help you stay up on the latest news/models/applications/tools.
* Read blogs to keep learning.  I really like [District Data Labs](http://districtdatalabs.silvrback.com/) and [Data Elixer](http://dataelixir.com/).
* There are some active Python Data meetups in the area:
	* [SF Python](http://www.meetup.com/sfpython/)
	* [SF Data Science](http://www.meetup.com/SF-Data-Science/)
	* [SF Data Mining](http://www.meetup.com/Data-Mining/)
	* Request sponsorship for study groups through [GA](https://gaalumni.typeform.com/to/dGyuWb)
	* [General GA Alumni Perks](http://generalassemb.ly/alumni)

	
Thank you all for such a wonderful time and I truly hope to stay in touch.

