# Lecture Schedule

## Introduction

- Mon, Jan 23 Lecture 1:  Half-day introduction.
    + Reading: syllabus
- Wed, Jan 25 Lecture 2: Introduction.
    + Reading: DSFS Ch. 1-4. (Read these 4 chapters sometime this week.  Ch. 2 and 3 are important for next week's lab.)
    + Reading: Read the following article: [Detecting influenza epidemics using search engine
query data](http://www.nature.com/nature/journal/v457/n7232/pdf/nature07634.pdf).  **Come to class prepared to discuss it.**  In particular, do the following:
        * Review the "Process of Data Science" slide from the first day's lecture.  Slides are available in this repo.  Align those steps with what was done in this study.  
        * Are any steps missing (or at least not discussed in this article)?
        * The paper describes the model they used for this data.  What is the model?  (I realize some terminology may be unfamiliar, but do your best to try to make sense of it.)
        * Think critically about GFT.  What problem is it attempting to solve?  Is it an effective solution?  What are some potential limitations?


## Data Processing

- Mon, Jan 30 Lecture 3: Data acquisition, cleaning, exploration.
    + Reading:
        * DSFS Ch. 9 Getting Data
        * DSFS Ch. 10 Working with Data (Exploring Your Data, p. 121-127)
        * DSFS Ch. 10 Working with Data (Cleaning and Munging, p. 127-129)
        * DSFS Ch. 10 Working with Data (Manipulating Data, p. 129-132)
        * [Python Regexp Tutorial](https://developers.google.com/edu/python/regular-expressions)
        * Supplemental: [another regexp tutorial](https://docs.python.org/2/howto/regex.html), docs for python [re module](https://docs.python.org/2/library/re.html#module-re)    
- Wed, Feb 01 Lecture 4:  Data processing.
    + Reading: 
        * Supplementary: Ch. 12.4 of Boat book.  Available [via moodle](https://moodle.colgate.edu/mod/resource/view.php?id=197855)
- Mon, Feb 06 Lecture 5:  Manipulating Tabular Data (SQL).
    + Reading: 
        * *I'm going to assign several different readings related to SQL.  You don't need to read all of it in fine detail.  Below I annotate each reading with what you should get out of it.  You can also use my lectures as a guide -- if I don't mention it in lecture, I won't hold you accountable for knowing it.*
        * DSFS Ch. 23 Databases and SQL -- *This provides a fairly quick overview of SQL and even uses python code to illustrate what each sql operation does.  This is a good place to start but it is missing useful features, such as the WITH keyword.*
        * [Boat book, Ch. 2](https://moodle.colgate.edu/mod/resource/view.php?id=195388) -- *This provides a basic overview of the relational model.  This should be a quick read.  If you come out of this chapter knowing the following concepts -- relation, schema, key -- you're probably good.*
        * [Boat book, Ch. 3](https://moodle.colgate.edu/mod/resource/view.php?id=195389) -- *This is a useful reference for SQL.  Sections 3.5 and 3.6 are less important.  Section 3.7 is essential.  Section 3.8 is about subqueries.  For this course, it probably suffices to focus on Section 3.8.6, which describes the WITH clause, a super useful feature.*
- Wed, Feb 08 Lecture 6:  Manipulating Tabular Data (SQL continued / Pandas)
    + Reading: 
        * The pandas library is a useful library for manipulating data in Python.  A book on it is available on moodle and I think the following chapter is the most useful.  It's unlikely that we will spend a lot of time on it in this course -- we simply don't have time and I want to focus on more fundamental, established languages like SQL.  However, I do want to bring it to your attention as a useful tool.  Therefore, consider this reading more as a reference rather than required reading.  The parts of pandas that I will expect you to know will be only those that I mention in class.
        * *Reference*: [Ch. 5 of Python for Data Analysis](https://moodle.colgate.edu/mod/url/view.php?id=194037)
- Mon, Feb 13 Lecture 7:  Fuzzy matching.
    + Reading: *TBD*

## Computational Statistics

- Wed, Feb 15 Lecture 8: Statistics
    + Reading: 
        * DSFS Ch. 5 Statistics (*You may want to review DSFS Ch. 4, which covers some linear algebra concepts that come up in this chapter, like dot.*)
        * [Simpspon's Paradox](http://vudlab.com/simpsons/)
- Mon, Feb 20 Lecture 9: Probability
    + Reading: 
        * DSFS Ch. 6 Probability
        * Supplemental: [Chances Are](https://opinionator.blogs.nytimes.com/2010/04/25/chances-are/)
- Wed, Feb 22 **Quiz 1** (in class)
    + *You will have the entire class period to complete the quiz though I expect you will finish in much less time than that.*
- Mon, Feb 27 Lecture 10: Probability, continued... 
    + Reading: Review DSFS Ch. 6
- Wed, Mar 01 Lecture 11: Hypothesis Testing
    + Reading: DSFS Ch. 7 Hypothesis and Inference
- Mon, Mar 06 Lecture 12: Linear Regression I & Gradient Descent
    + Reading: 
        * DSFS Ch. 14 Simple Linear Regression 
        * DSFS Ch. 8 Gradient Descent
    + Review Questions: you should be able to answer these questions after doing the reading.
        * Which of the following are differences between gradient descent (GD) and stochastic gradient descent (SGD)?
            - GD is regular gradient descent whereas SGD adds random noise to the gradient to help avoid local minima/maxima
            - SGD is preferred for large datasets
            - SGD requires an *additive* target function
            - SGD is typically faster than GD because it takes fewer steps
        * How do you take a step in GD? When does GD stop?
        * What is the role of step size in GD or SGD?  How do you choose the "right" step size?
        * In simple linear regression, given values for `alpha` and `beta` how do you measure how well the model fits the data?
        * Given values for `alpha` and `beta` and a small dataset (say 3 data points), you should be able to compute how well the model fits the data.
        * Taking Ch. 8 and Ch. 14 together, the book offers three different ways to fit a simple linear regression model.  What are they?
        * If you were to use GD to fit a simple linear regression model, what would the target function `target_fn` be?
- Tue, Mar 07 **Quiz 2** (in lab)
- Wed, Mar 08 Lecture 13: Linear Regression II
    + Reading: 
        * DSFS Ch. 15 Multiple Regression
- Mon, Mar 13 **No class: spring break!**
- Wed, Mar 15 **No class: spring break!**

## Machine Learning

- Mon, Mar 20 Lecture 14: Linear Regression III
    + Reading:
        * Review DSFS
        * Supplemental: Ch. 3 of [ISL](http://www-bcf.usc.edu/~gareth/ISL/)
- Wed, Mar 22 Lecture 15: Overview of Machine Learning
    + Reading: 
        * DSFS Ch. 11 Machine Learning
        * Supplemental: Ch. 2 of [ISL](http://www-bcf.usc.edu/~gareth/ISL/)
- Mon, Mar 27 Lecture 16: Parametric: Perceptron, Logistic Regression, Naive Bayes
    + Reading: 
        * DSFS Ch. 13 Naive Bayes    
        * DSFS Ch. 16 Logistic Regression (up to but not including Support Vector Machines)
        * ISL Ch. 4-4.3 Logistic Regression (this overlaps with Ch. 16 considerably but you are encouraged to read it anyway as it will reinforce concepts from DSFS Ch. 16 and add a little more perspective.)
        * Supplemental: ISL Ch. 2.2.3 (p. 37-39 about Bayes optimal classifier; Naive Bayes is a "naive" version of the Bayes optimal classifier)
- Wed, Mar 29 Lecture 17: Non-parametric: k-NN and trees
    + Reading: 
        * DSFS Ch.12 k-NN
        * DSFS Ch.17 Decision Trees
        * ISL Ch. 8-8.1 Tree-Based Methods (rest of chapter is supplemental)
        * Supplemental: ISL Ch. 2.2.3 (section on k-NN)
- Mon, Apr 03 Lecture 18: Learning Theory
    + Reading: Ch. 18.5 from Russell & Norvig's Artificial Intelligence, available on [moodle](https://moodle.colgate.edu/mod/resource/view.php?id=201282)
- Wed, Apr 05 Lecture 19: Overfitting, Selection, Cross Validation
    + Reading: 
        * ISL Ch. 5-5.1 Cross Validation
        * ISL Ch. 6-6.1 (In Ch. 6.1.3, Choosing the Optimal Model, it describes two approaches -- indirect and direct.  You can skip the indirect approach (p. 210-213) and focus on the direct, which is described under the section heading Validation and Cross-Validation on starting on p.213)

## Visualization

- Mon, Apr 10 Lecture 20: Visualization I
    + Reading: 
        * From Nathan Yau's *Data Points*, read [Ch. 3 Representing Data](https://msucreativecomp.files.wordpress.com/2016/08/data_points.pdf) also available online through the Colgate Library.
- Wed, Apr 12 Lecture 21: Visualization II
    + Reading: 
        * [A Layered Grammar of Graphics](http://vita.had.co.nz/papers/layered-grammar.pdf), by Hadley Wickham
        * [Misleading axes](http://callingbullshit.org/tools/tools_misleading_axes.html)
        * [Proportional Ink](http://callingbullshit.org/tools/tools_proportional_ink.html)
    + Supplemental readings on viz:
        * Dynamic graphics [Watch Hans Rosling](https://www.youtube.com/watch?v=jbkSRLYSojo)
        * [Chart Rules to Follow](http://flowingdata.com/2015/08/11/real-chart-rules-to-follow/)
        * Additional chapters of Nathan Yau's *Data Points* (see links above)

## Additional Topics

- Mon, Apr 17 Lecture 22: Privacy I
    + Reading: these readings are *supplemental*
        * Intuition, no math: [Differential Privacy: A Primer for a Non-technical Audience (Preliminary Version)](https://privacytools.seas.harvard.edu/publications/differential-privacy-primer-non-technical-audience-preliminary-version)
        * Math included: [A Firm Foundation for Private Data Analysis](http://cacm.acm.org/magazines/2011/1/103226-a-firm-foundation-for-private-data-analysis/fulltext)
- Wed, Apr 19 Lecture 23: Mini-presentations / Privacy II
    + During this class, each group will give a brief project presentation (see project page for details)
    + After the presentations, we can wrap up privacy.
- Fri, Apr 21: NASC Colloquium Talk: *Data Analysis with Privacy Protection: Seeing the Forest But Not The Trees*
	+ You are **required** to attend this event.
- Mon, Apr 24 Lecture 24: Clustering
    + Reading: 
        * DSFS Ch. 19
        * Supplemental: ISL Ch. 10.3 (this covers the same material as Ch. 19 of DSFS)
- Wed, Apr 26 Lecture 25: Fairness I
    + Reading: 
        * [When Algorithms Discriminate](https://www.nytimes.com/2015/07/10/upshot/when-algorithms-discriminate.html?_r=0)
        * [When Discrimination Is Baked Into Algorithms](https://www.theatlantic.com/business/archive/2015/09/discrimination-algorithms-disparate-impact/403969/)
        * Introduction and Part I of Barocas & Selbst [Big Data's Disparate Impact](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2477899) -- *Please come to class ready to discuss the ways in which a data mining (aka machine learning) algorithm can discriminate.*
- Mon, May 01 Lecture 26: Fairness II
    + Reading: *TBD*
- Wed, May 03 Lecture 27: :tada: **Project Presentations 2:45 - 6:30pm** :tada:
	+ *Please do not make any commitments during this time window*
- Tue, May 09 **Final Exam** time slot: 12:00 - 2:00pm.  *Hold for last quiz*
- Tue, May 09 **Final Project Report Due** 
