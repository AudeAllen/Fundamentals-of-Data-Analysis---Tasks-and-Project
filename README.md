# Fundamentals of Data Analysis - Tasks and Project <br /> 
<br /> 
The Fundamentals of Data Analysis - Tasks and Project contains all the assignments in the Higher Diploma in Data Analytics course for this module <br /> 
Here I will explain how I came to the solution of given tasks, reference the sources I researched for solving the problems and list the technologies I used for creating and testing the code <br />
<br />
<br />

# Table of contents - Tasks
* [Weekly tasks](#weekly-tasks)
    * [task1](#task1)
    * [task2](#task2)
    * [task3](#task3)



## Table of contents - Project
* [1 Project Introduction](#1-project-introduction)
    * [Problem Statement](#problem-statement)
* [2 Software needed to run the project](#2-software-needed-to-run-the-project)	
* [3 Background on   the Iris Dataset](#3-background-on-the-iris-dataset)	
* [4 Classification of Variables](#4-classification-of-variables)
* [5 Summary Statistics](#5-summary-statistics)





Weekly tasks
======
### ***task1***

  
1. The Collatz conjecture1 is a famous unsolved problem in mathematics. The problem is to prove that if you start with any positive
integer x and repeatedly apply the function f (x) below, you always
get stuck in the repeating sequence 1, 4, 2, 1, 4, 2, . . .<br /> 
x ÷ 2 if x is even<br /> 
3x + 1 otherwise<br /> 
For example, starting with the value 10, which is an even number,
we divide it by 2 to get 5. Then 5 is an odd number so, we multiply
by 3 and add 1 to get 16. Then we repeatedly divide by 2 to
get 8, 4, 2, 1. Once we are at 1, we go back to 4 and get stuck in the
repeating sequence 4, 2, 1 as we suspected.
Your task is to verify, using Python, that the conjecture is true for
the first 10,000 positive integers. <br /> 
<br />
<br />

======
### ***task2***


2. Give an overview of the famous penguins data set, explaining 
the types of variables it contains. Suggest the types of variables
that should be used to model them in Python, explaining your
rationale.

======
### ***task3***


3. For each of the variables in the penguins data set,3 suggest what probability distribution from the numpy random distributions list is the most appropriate to model the variable.


### References for Task


Task 2 - References

https://stats.oarc.ucla.edu/other/mult-pkg/whatstat/what-is-the-difference-between-categorical-ordinal-and-interval-variables/

https://en.wikipedia.org/wiki/Continuous_or_discrete_variable

https://www.cvent.com/en/blog/events/data-types-interval-ratio-data#:~:text=Ratio%20data%20has%20a%20defined,are%20examples%20of%20ratio%20data.

https://www.kaggle.com/code/parulpandey/penguin-dataset-the-new-iris

https://en.wikipedia.org/wiki/Level_of_measurement

Task 3 - References

https://docs.oracle.com/cd/E12825_01/epm.111/cb_user/frameset.htm?apas03.html

https://www.simplilearn.com/tutorials/statistics-tutorial/what-is-probability-distribution#:~:text=A%20probability%20distribution%20is%20a,variable%20within%20a%20given%20range.

https://bolt.mph.ufl.edu/6050-6052/unit-1/one-categorical-variable/#:~:text=In%20order%20to%20summarize%20the,converting%20the%20counts%20to%20percentages

https://www.statology.org/frequency-tables-python/

https://www.geeksforgeeks.org/how-to-create-frequency-tables-in-python/

https://www.kristakingmath.com/blog/symmetric-and-skewed-distributions

https://www.mygreatlearning.com/blog/gamma-distribution/#:~:text=Gamma%20Distribution%20is%20a%20Continuous,times%20between%20events%20are%20relevant.

https://en.wikipedia.org/wiki/Gamma_distribution

https://www.geeksforgeeks.org/python-numpy-np-lognormal-method/

https://github.com/AudeAllen/Fundamentals-of-Data-Analysis---Tasks-and-Project/blob/main/tasks.ipynb


========================================================================================================================



1 Project Introduction 
======
### ***Problem Statement***


1. The project is to create a notebook investigating the variables and data points within the well-known iris flower data set associated with Ronald A Fisher. 
2. In the notebook, you should discuss the classification of each variable within the data set according to common  variable types and scales of measurement in mathematics, statistics, and Python. 
3. Select, demonstrate, and explain the most appropriate summary statistics to describe each variable 
4. Select, demonstrate, and explain the most appropriate plot(s) for each variable.
5. The notebook should follow a cohesive narrative about the data set.


2 Software needed to run the project 
======
I will run through the different tools and packages that I am using for this project and anslyses.


3 Background on the Iris Dataset 
======

Brief description on the background of the Iris Dataset. Who created it and the different variables involved.

4 Classification of Variables
======
In this section of my notebook I will discuss the classification of each variable within the data set according to common variable types and scales of measurement in mathematics, statistics, and Python. 

The 4 variables in question are 

### ***Species***

### ***petallength***

### ***petalwidth***

### ***sepallength***

### ***sepalwidth***

5 Summary Statistics
======

The aim of this section of my project is to select, demonstrate, and explain the most appropriate summary statistics to describe each variable on the iris dataset.







7 References
======

https://rstudio-pubs-static.s3.amazonaws.com/450733_9a472ce9632f4ffbb2d6175aaaee5be6.html#:~:text=iris%20dataset%20gives%20the%20measurements,setosa%2C%20versicolor%2C%20and%20virginica

https://sa2253.medium.com/classification-of-iris-dataset-b4310ddf0482#:~:text=SUMMARY,networkis%20the%20best%20classification%20method

https://studyonline.unsw.edu.au/blog/types-of-data#:~:text=Psychologist%20Stanley%20Stevens%20developed%20the,to%20properly%20analyse%20the%20data