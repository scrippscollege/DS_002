# DS002 Intro to Data Science

| Class        | DS002: Intro to Data Science                                 |
| ------------ | ------------------------------------------------------------ |
| Instructor   | Douglas Goodwin <br />Visiting Assistant Professor in Media Studies, Scripps College <br />Lang 228 |
| Contact      | dgoodwin@scrippscollege.edu                                  |
| Class hours  | MW 11:00-12:15                                               |
| Office Hours | MW 1:00-3:00pm                                               |
| Discord      | https://discord.gg/gtMVkAMV                                  |
| Textbook     | **[Data Science from Scratch, 2nd Edition](https://www.oreilly.com/library/view/data-science-from/9781492041122/)** <br />Joel Grus. <br />ISBN: [9781492041139](https://www.oreilly.com/library/view/data-science-from/9781492041122/) |
| Classroom    | [Zoom](https://scrippscollege.zoom.us/j/7350754288?pwd=dExIZGFJYnV5Y0tTY2V1WVFXanFBdz09), +Steele 229 |
| Description  | This course is the second part of a two-semester introduction to computer programming and data science. Students will explore, using Python and other tools the nuances of gathering, visualizing and analyzing data to gain insight and intuition with data. Students will be introduced to various data manipulation/analysis, and statistical methods by building their own code from scratch. They will also consider the ethical implications and limitations of creating models of data. |

## Course Goals

Students completing this course will be able to:

- Define and explain key concepts in the data science
- Learn how to analyze real-world data.
- Gain fluency in basic programming skills in Python with a focus on statistical modeling and machine learning.
- Develop and use essential python programming skills in data analysis, data visualization, and machine learning

We begin by reviewing Python and establishing repositories on GitHub. After review and setup you will read two chapters from "Data Science from Scratch" (DSfS) each week and reproduce the code in the book to build your own code libraries. You are encouraged to write your own code (and tests) as long as you use the same function names. Your code won't b e efficient, but it will work and your APIs will match dedicated libraries such as *NumPy* ([Numerical Python](https://numpy.org/)), *pandas* ([Python Data Analysis Library](https://pandas.pydata.org/)), and *scikit-learn* ([machine learning in Python](https://scikit-learn.org/)).

Please complete the readings before and start your code before class on Monday. I will lecture on the chapters then we will go through your code together during Monday class. 

Wednesdays are lab days: work alone or in small groups to use your code to complete the lab assignments. 

## Points

| Activity              | Points     |
| --------------------- | ---------- |
| 10 Weekly Assignments | 30 points  |
| 1 Presentation        | 20 points  |
| 10 in-class exercises | 30 points  |
| Project               | 30 points  |
| **TOTAL**             | 110 points |

I give you a little extra room in case you miss an exercise or two. 

## Points and letter grades

This class will be easy if you keep up with the readings and come to class. 

| Point range | Grade |
| ----------- | ----- |
| 90-110      | A     |
| 80-90       | B     |
| 70-80       | C     |
| 60-70       | D     |
| < 60        | ...   |

###Weekly assignments

You will implement the code in the chapters from Data Science from Scratch (DSfS) to build a library of code to use in Deepnote. Push your assignments to your GitHub repository by Monday morning before class. We will use import your code and use it to complete in-class exercises with Deepnote. 

Please DON'T copy and paste code! Typing it will help you get familiar with and synthesize the code. 

Note the li beral use of the Python's `assert` statement in the sources files. A clean import will give you some assurance that your code is usable. There are more involved ways to test code, even a style of programming called TDD ([Test-Driven Development](https://en.wikipedia.org/wiki/Test-driven_development)). `assert` statements sprinkled throughout your source code give you TDD-lite!

### In-class exercises

Use your code library to solve Data Science problems related to each week's theme. I am creating these exercises now--please ask if you have an idea for an exercise!

### Presentation

DSfS uses a *Crow icon* to indicate relevnt subjects not covered adequately in the book. Each of you will select one of the "Crows" to present to the class on a Monday. 15 minutes, you may work alone or in small groups. 

### Projects

Complete a small, real-world project in the final week of the class. You can start with one of the in-class exercises or dream up a project of your own. Projects should use external data and be executed in Deepnote or on Google Colab. 

## Accessibility

If you have a documented disability (physical or cognitive) that may impair your ability to complete assignments or otherwise participate in the course and satisfy course criteria, please meet with us at your earliest convenience to identify, discuss, and document any feasible instructional modifications or accommodations. You should also contact the Accessible Education Office to request an official letter outlining authorized accommodations.

## Credits
I will lean heavily on the content in DSfS. Some of the material in this course is based on other classes. We have also heavily drawn on materials and examples found online and tried our best to give credit by linking to the original source. Please contact us if you find materials where the credit is missing or that you would rather have removed.

## Weeks

1. W01 01/17
   1. NO CLASS
   2. CH01 Introduction
2. W02 01/24
   1. CH02 A Crash Course in Python, pt1
   2. CH02 A Crash Course in Python, pt2
      1. Class Exercise

3. W03 01/31
   1. Python Assignment DUE BEFORE CLASS
   2. CH03 [Visualizing Data](https://github.com/joelgrus/data-science-from-scratch/blob/master/scratch/visualization.py)
   3. CH04 [Linear Algebra](https://github.com/joelgrus/data-science-from-scratch/blob/master/scratch/linear_algebra.py)
      1. Exercise
4. W04 02/07
   1. Viz Assignment DUE BEFORE CLASS
   2. CH05 [Statistics](https://github.com/joelgrus/data-science-from-scratch/blob/master/scratch/statistics.py)
   3. CH06 [Probability](https://github.com/joelgrus/data-science-from-scratch/blob/master/scratch/probability.py)
      1. Coinflip Class Exercise, Monty Hall Problem

1. W05 02/14

   1. Pandas Assignment DUE BEFORE CLASS
   2. CH07 [Hypothesis and Inference](https://github.com/joelgrus/data-science-from-scratch/blob/master/scratch/inference.py)
   3. CH08 [Gradient Descent](https://github.com/joelgrus/data-science-from-scratch/blob/master/scratch/gradient_descent.py)
      1. Class Exercise

2. W06 02/21

   1. Assignment DUE BEFORE CLASS
   2. CH09 [Getting Data](https://github.com/joelgrus/data-science-from-scratch/blob/master/scratch/getting_data.py)
   3. CH10 [Working With Data](https://github.com/joelgrus/data-science-from-scratch/blob/master/scratch/working_with_data.py)
      1. Class Exercise

7. W07 02/28

   1. Getting data Assignment DUE BEFORE CLASS
   1. CH11 [Machine Learning](https://github.com/joelgrus/data-science-from-scratch/blob/master/scratch/machine_learning.py)
   2. CH12 [k-Nearest Neighbors](https://github.com/joelgrus/data-science-from-scratch/blob/master/scratch/k_nearest_neighbors.py)
      1. Class Exercise

8. W08 03/07

   1. KNN Assignment DUE BEFORE CLASS
   1. CH13 [Naive Bayes](https://github.com/joelgrus/data-science-from-scratch/blob/master/scratch/naive_bayes.py)
   2. CH14 [Simple Linear Regression](https://github.com/joelgrus/data-science-from-scratch/blob/master/scratch/simple_linear_regression.py)
      1. Class Exercise

5. W09 03/14 SPRING BREAK

10. W10 03/21

   1. Lineasr Regression Assignment DUE BEFORE CLASS
   1. CH15 [Multiple Regression](https://github.com/joelgrus/data-science-from-scratch/blob/master/scratch/multiple_regression.py)
   2. CH16 [Logistic Regression](https://github.com/joelgrus/data-science-from-scratch/blob/master/scratch/logistic_regression.py)
      1. Class Exercise

11. W11 03/28

    1. Regression Assignment DUE BEFORE CLASS
    1. CH17 [Decision Trees](https://github.com/joelgrus/data-science-from-scratch/blob/master/scratch/decision_trees.py)
    2. CH18 [Neural Networks](https://github.com/joelgrus/data-science-from-scratch/blob/master/scratch/neural_networks.py)
       1. Class Exercise

12. W12 04/04

    1. Neural Networks Assignment DUE BEFORE CLASS
    1. CH19 [Deep Learning]
    2. CH20 [Clustering](https://github.com/joelgrus/data-science-from-scratch/blob/master/scratch/clustering.py)
       1. Class Exercise

13. W13 04/11

    1. Clustering Assignment DUE BEFORE CLASS
    1. CH21 [Natural Language Processing](https://github.com/joelgrus/data-science-from-scratch/blob/master/scratch/nlp.py)
    2. CH22 [Network Analysis](https://github.com/joelgrus/data-science-from-scratch/blob/master/scratch/network_analysis.py)
       1. Class Exercise

14. W14 04/18

    1. NLP Assignment DUE BEFORE CLASS
    1. CH23 [Recommender Systems](https://github.com/joelgrus/data-science-from-scratch/blob/master/scratch/recommender_systems.py)
    2. CH24 [Databases and SQL](https://github.com/joelgrus/data-science-from-scratch/blob/master/scratch/databases.py)
       1. Class Exercise

15. W15 04/25

    1. SQL Assignment DUE BEFORE CLASS
    1. CH25 [MapReduce](https://github.com/joelgrus/data-science-from-scratch/blob/master/scratch/mapreduce.py)
    2. CH26 Data Ethics
       1. Class Exercise

12. W16 04/02

    1. PROJECTS

    1. PROJECTS
       1. Share on Discord

