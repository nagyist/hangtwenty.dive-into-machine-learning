# Dive into Machine Learning [![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Hi there! This guide is for you if:

* You know Python or [you're learning it](https://nbviewer.org/github/jakevdp/WhirlwindTourOfPython/blob/master/Index.ipynb) :snake:
* You're new to [Machine Learning](https://en.wikipedia.org/wiki/Machine_learning)
* You care about [the ethics of ML](https://github.com/EthicalML/awesome-artificial-intelligence-guidelines)
    * **[8 Responsible Machine Learning Principles](https://ethical.institute/principles.html)**
    * [Questions to ask yourself when working with ML](https://cdt.info/ddtool/) [(source)](https://github.com/numfocus/algorithm-ethics)
* You learn by doing

If that's you, join me in getting a bit ahead of yourself, and see if you want to learn more about the field.

# Let's get started

Get your feet wet and boost your confidence.

## Tools you'll need

### If you prefer local installation

- [Python](https://www.python.org/). Python 3 is the best option.
- [Jupyter Notebook](https://jupyter.org/). (Formerly known as IPython Notebook.)
- Some scientific computing packages:
	- numpy
	- pandas
	- scikit-learn
	- matplotlib

You can install Python 3 and all of these packages in a few clicks with the [Anaconda Python distribution](https://www.anaconda.com/download/). Anaconda is popular in Data Science and Machine Learning communities. (Use whichever tool you want.)

### Cloud-based options

Some options you can use from your browser:

- **[Binder](https://mybinder.org/) is Jupyter Notebook's official choice to [try JupyterLab](https://jupyter.org/try)**
- [Deepnote](https://deepnote.com/) allows for real-time collaboration
- [Google Colab](https://colab.research.google.com/) provides "free" GPUs

For other options, see:

- [markusschanta/awesome-jupyter, "Hosted Notebook Solutions"](https://github.com/markusschanta/awesome-jupyter#hosted-notebook-solutions)
- [ml-tooling/best-of-jupyter, "Notebook Environments"](https://github.com/ml-tooling/best-of-jupyter)

## Let's go!

**[Learn how to use Jupyter Notebook](http://opentechschool.github.io/python-data-intro/core/notebook.html) (5-10 minutes).** (You can [learn by screencast](https://www.youtube.com/watch?v=qb7FT68tcA8) instead.)

Now, follow along with this brief exercise: **[An introduction to machine learning with scikit-learn](http://scikit-learn.org/stable/tutorial/basic/tutorial.html)**. Do it in `ipython` or Jupyter Notebook. It'll really boost your confidence.

[![I'll wait.](https://user-images.githubusercontent.com/2420688/29441281-00eff0c4-837f-11e7-9666-d653a1cd2372.jpeg)](http://scikit-learn.org/stable/tutorial/basic/tutorial.html)

## What just happened?

You just classified some hand-written digits using [scikit-learn](http://scikit-learn.org/stable/index.html). Neat huh?

# Dive in

## A Visual Introduction to Machine Learning

Let's learn a bit more about Machine Learning, and a couple of common ideas and concerns. Read ["A Visual Introduction to Machine Learning, Part 1"](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/) by [Stephanie Yee](https://twitter.com/stephaniejyee) and [Tony Chu](https://twitter.com/tonyhschu/).

[![A Visual Introduction to Machine Learning, Part 1](https://user-images.githubusercontent.com/2420688/29441234-a2028c98-837e-11e7-88f2-1ca5a94684f6.gif)](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)

It won't take long. It's a beautiful introduction ... Try not to drool too much!

## A Few Useful Things to Know about Machine Learning

OK. Let's dive deeper.

Read **["A Few Useful Things to Know about Machine Learning"](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf)** by [Prof. Pedro Domingos](https://homes.cs.washington.edu/~pedrod/). It's densely packed with valuable information, but not opaque. The author understands that there's a lot of "black art" and folk wisdom, and they invite you in.

Take your time with this one. Take notes. Don't worry if you don't understand it all yet.

The whole paper is packed with value, but I want to call out two points:

- **Data alone is not enough.** This is where science meets art in machine-learning. Quoting Domingos: "... the need for knowledge in learning should not be surprising. Machine learning is not magic; it can’t get something from nothing. What it does is get more from less. Programming, like all engineering, is a lot of work: we have to build everything from scratch. Learning is more like farming, which lets nature do most of the work. Farmers combine seeds with nutrients to grow crops. Learners combine knowledge with data to grow programs."
- **More data beats a cleverer algorithm.** Listen up, programmers. We like cool tools. Resist the temptation to reinvent the wheel, or to over-engineer solutions. Your starting point is to [Do the Simplest Thing that Could _Possibly_ Work](http://www.artima.com/intv/simplest3.html). Quoting Domingos: "Suppose you’ve constructed the best set of features you can, but the classifiers you’re getting are still not accurate enough. What can you do now? There are two main choices: design a better learning algorithm, or gather more data. [...] As a rule of thumb, a dumb algorithm with lots and lots of data beats a clever one with modest amounts of it. (After all, machine learning is all about letting data do the heavy lifting.)"

When you work on a real Machine Learning problem, you should focus your efforts on your **domain knowledge** and **data** before optimizing your choice of algorithms. Prefer to [Do Simple Things] until you _have_ to increase complexity. You should not rush into neural networks because you think they're cool. To improve your model, **get more data.** Then use your knowledge of the problem to [explore and process](https://www.thetalkingmachines.com/episodes/software-and-statistics-machine-learning) the data. You should only optimize the choice of algorithms after you have gathered enough data, and you've processed it well.

![What has the most impact in Machine Learning](https://user-images.githubusercontent.com/2420688/29441212-798d2bba-837e-11e7-90b1-21daaf8d7b73.png)

(Graphic inspired by a slide from [Alex Pinto's talk, "Secure Because Math: A Deep-Dive on ML-Based Monitoring"](https://www.youtube.com/watch?v=TYVCVzEJhhQ).)

[Do Simple Things]: http://wiki.c2.com/?DoSimpleThings

## Jargon note

* [What is the difference between Data Analytics, Data Analysis, Data Mining, Data Science, Machine Learning, and Big Data?](http://www.quora.com/What-is-the-difference-between-Data-Analytics-Data-Analysis-Data-Mining-Data-Science-Machine-Learning-and-Big-Data-1) 
* Another handy term: [_**Data Engineering**_](https://towardsdatascience.com/who-is-a-data-engineer-how-to-become-a-data-engineer-1167ddc12811?gi=67df10cc32ea), which may involve or support Machine Learning, but is not limited to Machine Learning.

## Just about time for a break...

Before you take a break, grab some podcasts. 

First, download [an interview with Prof. Domingos on the _Data Skeptic_ podcast](https://dataskeptic.com/blog/episodes/2018/the-master-algorithm) (2018). Prof. Domingos wrote [the paper we read earlier](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf). You might also start reading his book, [_The Master Algorithm_ by Prof. Pedro Domingos](https://www.goodreads.com/book/show/24612233-the-master-algorithm), a clear and accessible overview of machine learning. 

Next, subscribe to more machine learning and data science podcasts! These are great, low-effort resources that you can casually learn more from. To [learn effectively](https://www.coursera.org/learn/learning-how-to-learn), listen over time, with plenty of headspace. [By the way, don't speed up technical podcasts, that can hinder your comprehension.](https://www.theringer.com/2017/8/2/16095364/inefficiency-week-podcasts-speed-comprehension-f0ea43949e42)

Subscribe to _**[Talking Machines](http://www.thetalkingmachines.com/)**_.

I suggest this listening order:

* **Download the ["Starting Simple"](http://www.thetalkingmachines.com/episodes/starting-simple-and-machine-learning-meds) episode, and listen to that soon.** It supports what we read from Domingos. [Ryan Adams](http://people.seas.harvard.edu/~rpa/) talks about starting simple, as we discussed above. Adams also stresses the importance of feature engineering. Feature engineering is an exercise of the "knowledge" Domingos writes about. In a later episode, [they share many concrete tips for feature engineering](https://www.thetalkingmachines.com/episodes/software-and-statistics-machine-learning).
* Then, over time, you can listen to the entire podcast series (start from the beginning).

Want to subscribe to more podcasts? Here's [a good listicle](https://towardsdatascience.com/5-data-science-ai-and-machine-learning-podcasts-to-listen-to-now-e5078b18d184) of suggestions, [and another](https://mty.ai/blog/the-best-ai-podcasts/).

OK! Take a break, come back refreshed.

----

## Play to learn

Next, pick **one or two** of these Jupyter Notebooks and play along.

- [Dr. Randal Olson's Example Machine Learning notebook](https://github.com/rhiever/Data-Analysis-and-Machine-Learning-Projects/blob/master/example-data-science-notebook/Example%20Machine%20Learning%20Notebook.ipynb): "let's pretend we're working for a startup that just got funded to create a smartphone app that automatically identifies species of flowers from pictures taken on the smartphone.  We've been tasked by our head of data science to create a demo machine learning model that takes four measurements from the flowers (sepal length, sepal width, petal length, and petal width) and identifies the species based on those measurements alone."
	- [Launch in Binder, no installation steps required](https://mybinder.org/v2/gh/rhiever/Data-Analysis-and-Machine-Learning-Projects/master?filepath=example-data-science-notebook%2FExample%20Machine%20Learning%20Notebook.ipynb)
- Various notebooks by topic:
    - [trekhleb/machine-learning-experiments](https://github.com/trekhleb/machine-learning-experiments) - "This is a collection of interactive machine-learning experiments. Each experiment consists of 🏋️ Jupyter/Colab notebook (to see how a model was trained) and 🎨 demo page (to see a model in action right in your browser)."
    - [trekhleb/homemade-machine-learning](https://github.com/trekhleb/homemade-machine-learning)
- Notebooks in a series:
    - [ageron/handson-ml2](https://github.com/ageron/handson-ml2) - "A series of Jupyter notebooks that walk you through the fundamentals of Machine Learning and Deep Learning in Python using Scikit-Learn, Keras and TensorFlow 2."

Find more great Jupyter Notebooks when you're ready:

* **[Jupyter's official Gallery of Interesting Jupyter and IPython Notebooks: Statistics, Machine Learning and Data Science](https://github.com/jupyter/jupyter/wiki)** ([permalink](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks/ae03c01ed25024aa06a4479ea600895d59b38bc4))

----

# Immerse yourself

Now you should be hooked, and hungry to learn more. Pick one of the courses below and start on your way.

## [Recommended course: Prof. Andrew Ng's _Machine Learning_ on Coursera](https://www.coursera.org/learn/machine-learning)

**[Prof. Andrew Ng's](http://www.andrewng.org/about/) [_Machine Learning_](https://www.coursera.org/learn/machine-learning) is a popular and esteemed free online course. I've seen it [recommended](https://www.quora.com/How-do-I-learn-machine-learning-1/answer/Cory-Hicks-1) [often.](https://www.coursetalk.com/providers/coursera/courses/machine-learning?page=1&sort=-content_rating#reviews) [And](https://www.quora.com/How-do-I-learn-machine-learning-1/answer/Xavier-Amatriain) [emphatically.](https://www.forbes.com/sites/anthonykosner/2013/12/29/why-is-machine-learning-cs-229-the-most-popular-course-at-stanford/)**

It's helpful if you decide on a pet project to play around with, as you go, so you have a way to apply your knowledge. You could use one of these [Awesome Public Datasets](https://github.com/caesar0301/awesome-public-datasets). And remember, IPython Notebook is your friend.

Also, you should grab an in-depth textbook to use as a reference. The two best options are [_Understanding Machine Learning_ ](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/copy.html) and _[Elements of Statistical Learning](https://web.stanford.edu/~hastie/Papers/ESLII.pdf)_. You'll see these recommended as reference textbooks. [You only need to use one of the two options as your main reference; here's some context/comparison to help you pick which one is right for you.](https://github.com/hangtwenty/dive-into-machine-learning/issues/29) You can download each book free as PDFs at those links - so grab them!

### Tips for studying

* Busy schedule? Read [Ray Li's review of Prof. Andrew Ng's course](https://rayli.net/blog/data/coursera-machine-learning-review/) for some helpful tips.
* Review some of the ["Learning How to Learn"](https://www.coursera.org/learn/learning-how-to-learn/) videos. This is just about how to study in general. In the course, they [advocate the learn-by-doing approach](https://www.coursera.org/learn/learning-how-to-learn/lecture/8IUbH/interview-with-dr-terrence-sejnowski), as we're doing here. You'll get various other tips that are easy to apply, but go a long way to make your time investment more effective.

## Other courses

Here are some other free online courses I've seen recommended. (Machine Learning, Data Science, and related topics.)

* **Data science courses as Jupyter Notebooks:**
	* [Practical Data Science](http://radimrehurek.com/data_science_python/)
	* [Python Data Science Handbook, as Jupyter Notebooks](https://jakevdp.github.io/PythonDataScienceHandbook/)
	* Supplementary material: [donnemartin/data-science-ipython-notebooks](https://github.com/donnemartin/data-science-ipython-notebooks).
* [Prof. Pedro Domingos's introductory video series](https://homes.cs.washington.edu/~pedrod/). Domingos wrote the paper ["A Few Useful Things to Know About Machine Learning"](https://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf), recommended earlier in this guide.
* Kevin Markham's video series, [Intro to Machine Learning with scikit-learn](http://blog.kaggle.com/2015/04/08/new-video-series-introduction-to-machine-learning-with-scikit-learn/), starts with what we've already covered, then continues on at a comfortable place.
* [UC Berkeley's Data 8: The Foundations of Data Science](http://data8.org/) course and the textbook [Computational and Inferential Thinking](https://www.inferentialthinking.com/) teaches critical concepts in Data Science.
    * [Foundations of Data Science](https://www.edx.org/professional-certificate/berkeleyx-foundations-of-data-science) online course based on Data 8 is now offered via edX too.
* Prof. Mark A. Girolami's [Machine Learning Module (GitHub Mirror).](https://github.com/josephmisiti/machine-learning-module) Good for people with a strong mathematics background.
* Surveys of Data Science courseware (a bit more Choose Your Own Adventure)
	* Check out [Jack Golding's survey of Data Science courseware](https://www.quora.com/Is-it-worth-it-to-pay-9-*-49-for-a-data-science-specialization-on-Coursera/answer/Jack-Golding). Includes Coursera's [Data Science Specialization](https://www.coursera.org/specializations/jhu-data-science) with 9 courses in it. The Specialization certificate isn't free, but you can take the courses 1-by-1 for free if you don't care about the certificate. The survey also covers [Harvard CS109](http://cs109.github.io/2014/) which I've seen recommended elsewhere.
	* [Another epic Quora thread: How can I become a data scientist?](https://www.quora.com/How-can-I-become-a-data-scientist?redirected_qid=59455)
	* Data Science Weekly's [Big List of Data Science Resources](https://www.datascienceweekly.org/data-science-resources/the-big-list-of-data-science-resources) has a [List of Data Science MOOCs](https://www.datascienceweekly.org/data-science-resources/data-science-moocs)
* [Advanced Statistical Computing (Vanderbilt BIOS8366)](http://stronginference.com/Bios8366/lectures.html). Interactive (lots of IPython Notebook material)
* [Data Science (Harvard CS109)](http://cs109.github.io/2014/)

## Getting Help: Questions, Answers, Chats

Start with the support forums and chats related to the course(s) you're taking.

Check out [datascience.stackexchange.com](https://datascience.stackexchange.com/) and [stats.stackexchange.com – such as the tag, _machine-learning_.](https://stats.stackexchange.com/questions/tagged/machine-learning?sort=frequent&pageSize=15) There are some subreddits like [/r/machinelearning](https://www.reddit.com/r/machinelearning).

There are also many relevant discussions on Quora, for example: [What is the difference between Data Analytics, Data Analysis, Data Mining, Data Science, Machine Learning, and Big Data?](http://www.quora.com/What-is-the-difference-between-Data-Analytics-Data-Analysis-Data-Mining-Data-Science-Machine-Learning-and-Big-Data-1)

For help and community in meatspace, seek out meetups. Data Science Weekly's [Big List of Data Science Resources](http://www.datascienceweekly.org/data-science-resources/the-big-list-of-data-science-resources) may help you.

## Supplement: Learning Pandas well

You'll want to get more familiar with Pandas.

* **Essential**: [10 Minutes to Pandas](http://pandas.pydata.org/pandas-docs/stable/10min.html)
* **Essential**: [Things in Pandas I Wish I'd Had Known Earlier](http://nbviewer.jupyter.org/github/rasbt/python_reference/blob/master/tutorials/things_in_pandas.ipynb) (IPython Notebook)
* Another helpful tutorial: [Real World Data Cleanup with Python and Pandas](https://trendct.org/2016/08/05/real-world-data-cleanup-with-python-and-pandas/)
* [Video series from Data School, about Pandas](https://www.youtube.com/playlist?list=PL5-da3qGB5ICCsgW1MxlZ0Hq8LL5U3u9y). "Reference guide to 30 common pandas tasks (plus 6 hours of supporting video)."
* [Useful Pandas Snippets](http://www.swegler.com/becky/blog/2014/08/06/useful-pandas-snippets/)
* Here are some docs I found especially helpful as I continued learning:
	* [Cookbook](http://pandas.pydata.org/pandas-docs/stable/cookbook.html)
	* [Data Structures](http://pandas.pydata.org/pandas-docs/stable/dsintro.html), esp. [DataFrame](http://pandas.pydata.org/pandas-docs/stable/dsintro.html#dataframe) section
	* [Reshaping by pivoting DataFrames](https://pandas.pydata.org/pandas-docs/stable/user_guide/reshaping.html)
	* [Computational tools](http://pandas.pydata.org/pandas-docs/stable/computation.html) and [StackExchange thread: "What is covariance in plain language?"](https://stats.stackexchange.com/questions/29713/what-is-covariance-in-plain-language)
	* [Group By (split, apply, and combine DataFrames)](http://pandas.pydata.org/pandas-docs/stable/groupby.html)
	* [Visualizing your DataFrames](https://pandas.pydata.org/pandas-docs/stable/user_guide/visualization.html)
* Bookmarks for later when you need to scale
	* [The `odo` library](http://odo.readthedocs.io/) for converting between _many_ formats.
	* [`dask`](https://dask.org/): A Pandas-like interface, but for larger-than-memory data and "under the hood" parallelism. Very interesting, but only needed when you're getting advanced. 

## Supplement: Cheat Sheets

Some good cheat sheets I've come across. (Please [submit a Pull Request](https://github.com/hangtwenty/dive-into-machine-learning/pulls) to add other useful cheat sheets.)

- [scikit-learn algorithm cheat sheet](http://scikit-learn.org/stable/tutorial/machine_learning_map/)
- [Metacademy: a package manager for [machine learning] knowledge](http://hunch.net/?p=2714). A mind map of machine learning concepts, with great detail on each.
- [Matplotlib / Pandas / Python cheat sheets](https://drive.google.com/drive/folders/0ByIrJAE4KMTtaGhRcXkxNHhmY2M).

# Assorted Opinions and Other Resources

## More Data Science materials

Here are some additional Data Science resources:

* **Extremely accessible data science book: [_Data Smart_ by John Foreman](http://www.john-foreman.com/data-smart-book.html)**
* **[Python Data Science Handbook, as Jupyter Notebooks](https://jakevdp.github.io/PythonDataScienceHandbook/)**
* [Data Science Workflow: Overview and Challenges](https://cacm.acm.org/blogs/blog-cacm/169199-data-science-workflow-overview-and-challenges/fulltext) (read the article *and also* the comment by Joseph McCarthy)
* Swami Chandrasekaran's ["Becoming a Data Scientist"](http://nirvacana.com/thoughts/becoming-a-data-scientist/) is a concise, printable picture of a data science curriculum (caveat: it is from 2013, but still useful)


## Bayesian Statistics and Machine Learning

From [the "Bayesian Machine Learning" overview on Metacademy](https://metacademy.org/roadmaps/rgrosse/bayesian_machine_learning):

> ... Bayesian ideas have had a big impact in machine learning in the past 20 years or so because of the flexibility they provide in building structured models of real world phenomena. Algorithmic advances and increasing computational resources have made it possible to fit rich, highly structured models which were previously considered intractable.

You can learn more by studying one of the following resources. Both resources use Python, [PyMC](https://github.com/pymc-devs/pymc), and Jupyter Notebooks.
* The **free book,** _[Probabilistic Programming and Bayesian Methods for Hackers](http://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/)._ Made with a "computation/understanding-first, mathematics-second point of view." It's available in print too!
* [Bayesian Modelling in Python](https://github.com/markdregan/Bayesian-Modelling-in-Python)
* Like learning by playing? Me too. Try [19 Questions](https://github.com/fulldecent/19-questions), "a machine learning game which asks you questions and guesses an object you are thinking about," and **explains which Bayesian statistics techniques are being used.**

## Risks

"Machine learning systems automatically learn programs from
data." Pedro Domingos, in ["A Few Useful Things to Know about Machine Learning."](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf) The programs you generate will require maintenance. Like any way of creating programs faster, you can rack up [technical debt](https://en.wikipedia.org/wiki/Technical_debt).

Here is the abstract of [Machine Learning: The High-Interest Credit Card of Technical Debt](https://static.googleusercontent.com/media/research.google.com/en/us/pubs/archive/43146.pdf):

> Machine learning offers a fantastically powerful toolkit for building complex systems quickly. This paper argues that it is dangerous to think of these quick wins as coming for free. Using the framework of technical debt, we note that it is remarkably easy to incur massive ongoing maintenance costs at the system level when applying machine learning. The goal of this paper is highlight several machine learning specific risk factors and design patterns to be avoided or refactored where possible. These include boundary erosion, entanglement, hidden feedback loops, undeclared consumers, data dependencies, changes in the external world, and a variety of system-level anti-patterns.

If you're following this guide, you should read that paper. You can also [listen to a podcast episode interviewing one of the authors of this paper](https://softwareengineeringdaily.com/2015/11/17/machine-learning-and-technical-debt-with-d-sculley/).

- **[Awesome Production Machine Learning](https://github.com/EthicalML/awesome-production-machine-learning), "a curated list of awesome open source libraries to deploy, monitor, version and scale your machine learning."** It includes a section about [privacy-preserving ML](https://github.com/EthicalML/awesome-production-machine-learning#privacy-preserving-machine-learning), by the way!
- **["Rules of Machine Learning: Best Practices for [Reliable] ML Engineering,"](http://martin.zinkevich.org/rules_of_ml/rules_of_ml.pdf)** by Martin Zinkevich, regarding ML engineering practices. There's an [accompanying video](http://cs.stanford.edu/~jsteinhardt/wildml2016nips/videos/1_2_Martin.wmv).
- **[Surviving Data Science "at the Speed of Hype"](http://www.john-foreman.com/blog/surviving-data-science-at-the-speed-of-hype)** by John Foreman, Data Scientist at MailChimp
- [The High Cost of Maintaining Machine Learning Systems](http://www.kdnuggets.com/2015/01/high-cost-machine-learning-technical-debt.html)
- [11 Clever Methods of Overfitting and How to Avoid Them](http://hunch.net/?p=22)
- [The Perilous World of Machine Learning for Fun and Profit: Pipeline Jungles and Hidden Feedback Loops](http://www.john-foreman.com/blog/the-perilous-world-of-machine-learning-for-fun-and-profit-pipeline-jungles-and-hidden-feedback-loops)

### Welcome to the Danger Zone

So you are dabbling with Machine Learning. You've got Hacking Skills. Maybe you've got some "knowledge" in Domingos' sense (some "Substantive Expertise" or "Domain Knowledge"). This diagram is modified slightly from Drew Conway's "Data Science Venn Diagram." It isn't a _perfect_ fit for us, but it may get the point across:

[![Drew Conway's Data Science Venn Diagram, modified slightly](https://user-images.githubusercontent.com/2420688/29441268-f429d88c-837e-11e7-83ff-30874d832c89.png)](http://drewconway.com/zia/2013/3/26/the-data-science-venn-diagram)

**Please** don't sell yourself as a Machine Learning expert while you're still in the Danger Zone. Don't build bad products or publish junk science. Please do bookmark the Institute for Ethical AI & Machine Learning's **[Responsible Machine Learning Principles](https://ethical.institute/principles.html)**. This guide can't tell you how you'll know you've "made it" into Machine Learning competence ... let alone expertise. It's hard to evaluate proficiency without schools or other institutions. So, practice!

#### Towards Expertise

You need **practice.** [On Hacker News, user olympus commented to say you could use competitions to practice and evaluate yourself](https://news.ycombinator.com/item?id=10508565). [Kaggle](https://www.kaggle.com/competitions) and [ChaLearn](http://www.chalearn.org/) are hubs for Machine Learning competitions. You can find some [examples of code for popular Kaggle competitions here](https://github.com/apeeyush/machine-learning). For smaller exercises, [try HackerRank](https://www.hackerrank.com/domains/ai/machine-learning/page/1).

You also need **understanding.** You should review what Kaggle competition winners say about their solutions, [for example, the "No Free Hunch" blog](http://blog.kaggle.com/). These might be over your head at first but once you're starting to understand and appreciate these, you know you're getting somewhere.

Competitions and challenges are just one way to practice. You shouldn't limit yourself, though - and you should also understand that [Machine Learning isn't **all** about Kaggle competitions](https://jvns.ca/blog/2014/06/19/machine-learning-isnt-kaggle-competitions).

Here's a complementary way to practice: **do practice studies.**

1. **Ask a question. Start your own study.** The ["most important thing in data science is the question"](https://github.com/DataScienceSpecialization/courses/blob/master/01_DataScientistToolbox/03_02_whatIsData/index.Rmd#the-data-is-the-second-most-important-thing) ([Dr. Jeff T. Leek](https://github.com/jtleek)). So start with a question. Then, find [real data](https://github.com/caesar0301/awesome-public-datasets). Analyze it. Then ...
2. **Communicate results.** When you have a novel finding, reach out for peer review.
3. **Fix issues.** Learn. Share what you learn.

And repeat. Re-phrasing this, it fits with the [scientific method](https://en.wikipedia.org/wiki/Scientific_method): formulate a question (or problem statement), create a hypothesis, gather data, analyze the data, and communicate results. (You should [watch this video about the scientific method in data science](http://101.datascience.community/2012/06/27/the-data-scientific-method/), and/or [read this article](http://customerthink.com/getting-insights-using-data-science-skills-and-the-scientific-method/).)

How can you come up with interesting questions? Here's one way. Every Sunday, [browse datasets](https://github.com/caesar0301/awesome-public-datasets) and write down some questions. Also, sign up for [Data is Plural](https://tinyletter.com/data-is-plural), a newsletter of interesting datasets; look at these, datasets, and write down questions. Stay curious. When a question inspires you, start a study.

This advice, to do practice studies and learn from peer review, is based on [a conversation](https://github.com/hangtwenty/dive-into-machine-learning/issues/11#issuecomment-153934120) with [Dr. Randal S. Olson](http://www.randalolson.com/). Here's more advice from Olson, [quoted with permission:](https://github.com/hangtwenty/dive-into-machine-learning/issues/11#issuecomment-154135498)

> I think the best advice is to tell people to always present their methods clearly and to avoid over-interpreting their results. Part of being an expert is knowing that there's rarely a clear answer, especially when you're working with real data.

As you repeat this process, your practice studies will become more scientific, interesting, and focused. The most important part of this process is peer review.

#### Ask for Peer Review

Here are some communities where you can reach out for peer review:

* [/r/LearnMachineLearning](https://www.reddit.com/r/learnmachinelearning/)
* [/r/DataIsBeautiful](https://reddit.com/r/DataIsBeautiful)
* [/r/DataScience](https://reddit.com/r/DataScience)
* [/r/MachineLearning](https://reddit.com/r/MachineLearning)
* [Cross-Validated: stats.stackexchange.com](https://stats.stackexchange.com/)
* [Hacker News: news.ycombinator.com](https://news.ycombinator.com). You'll probably want to submit as "Show HN"

Post to any of those, and ask for feedback. You'll get feedback. You'll learn a ton. As experts review your work you will learn a lot about the field. You'll also be practicing a crucial skill: accepting critical feedback.

When I read the feedback on my Pull Requests, first I repeat to myself, "I will not get defensive, I will not get defensive, I will not get defensive." You may want to do that before you read reviews of your Machine Learning work too.

### It's dangerous to go alone, take these!

**Bookmark these:**

* **[EthicalML/Awesome-Artificial-Intelligence-Guidelines.](https://github.com/EthicalML/awesome-artificial-intelligence-guidelines)**
    * Also by same org: [EthicalML/awesome-production-machine-learning](https://github.com/EthicalML/awesome-production-machine-learning#privacy-preserving-machine-learning)
* **[visenger/Awesome-ML-Model-Governance](https://github.com/visenger/Awesome-ML-Model-Governance)**
    * Also by same author: [visenger/Awesome-MLOps](https://github.com/visenger/awesome-mlops) ([ml-ops.org](https://ml-ops.org/))

----

## Collaborate with Domain Experts

Machine Learning can be powerful, but it is not magic.

Whenever you apply Machine Learning to solve a problem, you are going to be working in some specific problem domain. To get good results, you or your team will need "substantive expertise" AKA "domain knowledge." Learn what you can, for yourself... But you should also **collaborate.** You'll have better results if you collaborate with domain experts. (What's a domain expert? See the [Wikipedia entry](https://en.wikipedia.org/wiki/Subject-matter_expert), or [c2 wiki's rather subjective but useful blurb](http://wiki.c2.com/?DomainExpert).)

### :bow: A note about Machine Learning and User Experience (UX)

I couldn't say it better:

> **Machine learning won’t figure out what problems to solve.** If you aren’t aligned with a human need, you’re just going to build a very powerful system to address a very small—or perhaps nonexistent—problem.

Quote is from ["The UX of AI" by  Josh Lovejoy](https://design.google/library/ux-ai/), whole article is a great read!

In other words, **[You Are Not The User](https://www.nngroup.com/articles/false-consensus/).**

Today we are [_surrounded_](https://en.wikipedia.org/wiki/Machine_learning#Applications) by software that utilizes Machine Learning. Often, the results are directly user-facing, and intended to enhance UX.

Before you start working ML into _your_ software, you should get a better understanding of UX, as well as how ML and UX can relate. As an informal way to get into this subject, start with this:

* [Rule #23 of _Martin Zinkevich's Rules of ML Engineering_](https://developers.google.com/machine-learning/guides/rules-of-ml/#human_analysis_of_the_system): **"You are not a typical end user."**
* There are some great [thoughtful discussions of this on Quora](https://www.quora.com/search?q=machine+learning+ux)

Then, if you you know a coworker or friend who works in UX, take them out for coffee or lunch and pick their brain. I think they'll have words of encouragement as well as caution. You won't be an expert by any means, but maybe it'll help you konw if/when to reach out for help, review, or guidance. 

Spoiler: you should work with UX specialists whenever you can!

----

## Deep Learning

In early editions of this guide, there was no specific "Deep Learning" section. I omitted it intentionally. I think it is not effective for us to jump too far ahead. I also know that if you become an expert in traditional Machine Learning, you'll be capable of moving onto advanced subjects like Deep Learning, whether or not I've put that in this guide. We're just trying to get you started here!

Maybe this is a way to check your progress: ask yourself, does Deep Learning seem like magic? If so, take that as a sign that you aren't ready to work with it professionally. Let the fascination motivate you to learn more. I have read some argue you can learn Deep Learning in isolation; I have read others recommend it's best to master traditional Machine Learning first. Why not start with traditional Machine Learning, and develop your reasoning and intuition there? You'll only have an easier time learning Deep Learning after that. After all of it, you'll able to tackle all sorts of interesting problems.

In any case, when you're ready to dive into Deep Learning, here are some helpful resources.

* **[Dive into Deep Learning](https://d2l.ai/) - An interactive book about deep learning**
    * "Interactive deep learning book with code, math, and discussions"
    * "Implemented with NumPy/MXNet, PyTorch, and TensorFlow"
    * "Adopted at 200 universities from 50 countries"
* **[labmlai/annotated_deep_learning_paper_implementations](https://github.com/labmlai/annotated_deep_learning_paper_implementations)** - "Deep learning papers implemented, with side-by-side notes" - "We are actively maintaining this repo and adding new implementations almost weekly."
* **["Have Fun With [Deep] Learning" by David Humphrey.](https://github.com/humphd/have-fun-with-machine-learning)** This is an excellent way to "get ahead of yourself" and hack-first. Then you will feel excited to move onto...
*  **[Prof. Andrew Ng's](https://www.andrewng.org/about/) [courses on Deep Learning](https://www.coursera.org/specializations/deep-learning)!** There five courses, as part of the [Deep Learning Specialization on Coursera](https://www.coursera.org/specializations/deep-learning). These courses are part of his new venture, [deeplearning.ai](https://www.deeplearning.ai)
* **[Machine Learning Crash Course from Google.](https://developers.google.com/machine-learning/crash-course/)** Google's fast-paced, practical introduction to machine learning which covers building deep neural networks with TensorFlow.
* **[_Deep Learning_](http://www.deeplearningbook.org/), a free book published MIT Press.** By Ian Goodfellow, Yoshua Bengio and Aaron Courville
* [YerevaNN's Deep Learning Guide](http://yerevann.com/a-guide-to-deep-learning/)
* [Quora: "What are the best ways to pick up Deep Learning skills as an engineer?"](https://www.quora.com/What-are-the-best-ways-to-pick-up-Deep-Learning-skills-as-an-engineer) — answered by Greg Brockman (Co-Founder & CTO at OpenAI, previously CTO at Stripe)
* [Creative Applications of Deep Learning with Tensorflow](https://github.com/pkmital/CADL)

### Easier sharing of deep learning models and demos

* **[replicate.ai](https://replicate.ai)** "makes it easy to share a running machine learning model" for the sake of reproducible research. Check it out.
    * For beginners, you can try some models using GANs and other Deep Learning concepts.
    * Bookmark-worthy because you can use it to share your learning or research, too.
    * Open source tools: [`cog`](https://github.com/replicate/cog), [`keepsake`](https://github.com/replicate/keepsake)

### "Big" Data?

If you are working with data-intensive applications at all, I'll recommend this book:

* **[_Designing Data-Intensive Applications_](http://dataintensive.net)** by Martin Kleppman. (You can start reading it online, free, via Safari Books.) It's not specific to Machine Learning, but you can bridge that gap yourself.

Lastly, here are some other useful links regarding Big Data and ML.

* [10 things statistics taught us about big data analysis](https://simplystatistics.org/2014/05/22/10-things-statistics-taught-us-about-big-data-analysis/) (and some more food for thought: ["What Statisticians think about Data Scientists"](http://www.datasciencecentral.com/profiles/blogs/what-statisticians-think-about-data-scientists))
* ["Talking Machines" #12](http://www.thetalkingmachines.com/blog/2015/6/4/the-economic-impact-of-machine-learning-and-using-the-kernel-trick-to-dig-in-to-big-data): Interviews Prof. Andrew Ng (from [our main course, which has its own module on big data](https://www.coursera.org/learn/machine-learning)); this episode covers some problems relevant to _high-dimensional_ data
* ["Talking Machines" #15: "Really Really Big Data and Machine Learning in Business"](http://www.thetalkingmachines.com/blog/2015/7/16/really-really-big-data-and-machine-learning-in-business)
* Free eBook, [_Getting Data Right: Tackling the Challenges of
Big Data Volume and Variety_](https://www.tamr.com/landing-pages/getting-data-right/) by Michael Stonebraker, Tom Davenport, James Markarian, and others, published by O'Reilly. You can [listen to an accompanying podcast](http://radar.oreilly.com/2015/06/the-future-of-data-at-scale.html) too.

----

## Finding Open-Source Libraries

* Bookmark **[awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning)**, a curated list of [awesome](https://github.com/bayandin/awesome-awesomeness) Machine Learning libraries and software.
* Bookmark [Pythonidae](https://github.com/svaksha/pythonidae/blob/master/AI.md#machine-learning), a curated list of [awesome](https://github.com/bayandin/awesome-awesomeness) libraries and software in the Python language - with a section on Machine Learning.
* For Machine-Learning libraries that might not be on PyPI, GitHub, etc., there's [MLOSS (Machine Learning Open Source Software)](http://mloss.org/software/). Seems to feature many academic libraries.
* Julia: [Julia.jl](https://github.com/svaksha/Julia.jl/blob/master/AI.md#machine-learning), a curated list of [awesome](https://github.com/bayandin/awesome-awesomeness) libraries and software in the Julia language - with a section on Machine Learning.

----

## More ways to "Dive into Machine Learning"

Here are some other guides to Machine Learning. They can be alternatives or complements to this guide.

* ["How would your curriculum for a machine learning beginner look like?"](https://sebastianraschka.com/faq/docs/ml-curriculum.html) by Sebastian Raschka. A selection of the core online courses and books for getting started with machine learning and gaining expert knowledge. It contextualizes Raschka's own book, [_Python Machine Learning_](https://github.com/rasbt/python-machine-learning-book) (which I would have linked to anyway!) See also [`pattern_classification` GitHub repository](https://github.com/rasbt/pattern_classification) maintained by the author, which contains IPython notebooks about various machine learning algorithms and various data science related resources.
* [Materials for Learning Machine Learning](http://jacksimpson.co/materials-for-learning-machine-learning/) by Jack Simpson
* Courses by cloud vendors (may be specific to their tools/platforms)
    * [Machine Learning Crash Course from Google](https://developers.google.com/machine-learning/crash-course/) with TensorFlow APIs. This is Google's fast-paced, practical introduction to machine learning which features a series of lessons with video lectures, real-world case studies, and hands-on practice exercises.
    *  [Amazon AWS](https://aws.amazon.com/training/learning-paths/machine-learning/) Amazon have open up their internal training to the public and also offer certification. 30 courses - 45+ hours of content.
* [Machine Learning for Developers](http://xyclade.github.io/MachineLearning/) is another good introduction, perhaps better if you're more familiar with Java or Scala. It introduces machine learning for a developer audience using Smile, a machine learning library that can be used both in Java and Scala.
* [Example Machine Learning notebook, exercise, and guide](https://github.com/rhiever/Data-Analysis-and-Machine-Learning-Projects/blob/master/example-data-science-notebook/Example%20Machine%20Learning%20Notebook.ipynb) by Dr. Randal S. Olson. Mentioned in Notebooks section as well, but it has a similar goal to this guide (introduce you, and show you where to go next). Rich "Further Reading" section.
* [Machine Learning for Software Engineers](https://github.com/ZuzooVn/machine-learning-for-software-engineers) by Nam Vu. It’s the top-down and results-first approach designed for software engineers.
* For some news sources to follow, check out [Sam DeBrule's list](https://machinelearnings.co/a-humans-guide-to-machine-learning-e179f43b67a0) here.
* [Distill.pub](https://distill.pub/about/) publishes explorable explanations that are really great.
  * ["Feature Visualization: How neural networks build up their understanding of images"](https://distill.pub/2017/feature-visualization/)
* One or both of these open-source books, also available on LeanPub:
  1. https://github.com/rasbt/python-machine-learning-book-2nd-edition 
  2. https://github.com/rasbt/deep-learning-book
* [ageron/handson-ml2](https://github.com/ageron/handson-ml2) aka [_Hands-On Machine Learning with Scikit-Learn, Keras and TensorFlow_ by Aurélien Geron](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/)

