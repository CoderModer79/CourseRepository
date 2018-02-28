1. Boston Housing

Description

The Boston housing market is highly competitive, and we want to be the best real estate agent in the area. To compete with our peers, we decide to use a few basic machine learning concepts to assist us and a client with finding the best selling price for their home. Fortunately, we have come across the Boston Housing dataset which contains aggregated data on various features for houses in Greater Boston communities. Our task is to build an optimal model based on a statistical analysis with the tools available. This model will then be used to estimate the best selling price for your clients' homes.

Data

The modified Boston housing dataset consists of 490 data points, with each datapoint having 3 features. This dataset is a modified version of the Boston Housing dataset found on the UCI Machine Learning Repository.

Features

RM: average number of rooms per dwelling LSTAT: percentage of population considered lower status PTRATIO: pupil-student ratio by town Target Variable 4. MEDV: median value of owner-occupied homes

Problems :

We would like to build a model using linear regression algorithm to be able to make accurate corrections for the median value of homes using features of the Boston Housing Data Set.

2. Student Intervention

A local school district has a goal to reach a 95% graduation rate by the end of the decade by identifying students who need 
intervention before they drop out of school. As a software engineer contacted by the school district, our task is to model 
the factors that predict how likely a student is to pass their high school final exam, by constructing an intervention system 
that leverages supervised learning techniques. The board of supervisors has asked that you find the most effective model that
uses the least amount of computation costs to save on the budget. We will need to analyze the dataset on students' performance
and develop a model that will predict the likelihood that a given student will pass, quantifying whether an intervention is 
necessary.

Data

The dataset used in this project is included as student-data.csv. This dataset has the following attributes:

Features:
school : student's school (binary: "GP" or "MS")
sex : student's sex (binary: "F" - female or "M" - male)
age : student's age (numeric: from 15 to 22)
address : student's home address type (binary: "U" - urban or "R" - rural)
famsize : family size (binary: "LE3" - less or equal to 3 or "GT3" - greater than 3)
Pstatus : parent's cohabitation status (binary: "T" - living together or "A" - apart)
Medu : mother's education (numeric: 0 - none, 1 - primary education (4th grade), 2 - 5th to 9th grade, 3 - secondary education or 4 - higher education)
Fedu : father's education (numeric: 0 - none, 1 - primary education (4th grade), 2 - 5th to 9th grade, 3 - secondary education or 4 - higher education)
Mjob : mother's job (nominal: "teacher", "health" care related, civil "services" (e.g. administrative or police), "at_home" or "other")
Fjob : father's job (nominal: "teacher", "health" care related, civil "services" (e.g. administrative or police), "at_home" or "other")
reason : reason to choose this school (nominal: close to "home", school "reputation", "course" preference or "other")
guardian : student's guardian (nominal: "mother", "father" or "other")
traveltime : home to school travel time (numeric: 1 - <15 min., 2 - 15 to 30 min., 3 - 30 min. to 1 hour, or 4 - >1 hour)
studytime : weekly study time (numeric: 1 - <2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, or 4 - >10 hours)
failures : number of past class failures (numeric: n if 1<=n<3, else 4)
schoolsup : extra educational support (binary: yes or no)
famsup : family educational support (binary: yes or no)
paid : extra paid classes within the course subject (Math or Portuguese) (binary: yes or no)
activities : extra-curricular activities (binary: yes or no)
nursery : attended nursery school (binary: yes or no)
higher : wants to take higher education (binary: yes or no)
internet : Internet access at home (binary: yes or no)
romantic : with a romantic relationship (binary: yes or no)
famrel : quality of family relationships (numeric: from 1 - very bad to 5 - excellent)
freetime : free time after school (numeric: from 1 - very low to 5 - very high)
goout : going out with friends (numeric: from 1 - very low to 5 - very high)
Dalc : workday alcohol consumption (numeric: from 1 - very low to 5 - very high)
Walc : weekend alcohol consumption (numeric: from 1 - very low to 5 - very high)
health : current health status (numeric: from 1 - very bad to 5 - very good)
absences : number of school absences (numeric: from 0 to 93)
passed : did the student pass the final exam (binary: yes or no)

Problem :

3. Titanic Survival:

