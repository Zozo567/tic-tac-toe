# Tic tac toe

> Read, explore and perform Tic-Toc data from UCI repository, as well as to evaluate different algorithms which performs on the best way for Bianry Classification task.

## Data understanding
The aim is collect initial data, get familiar with data and identify the quality of data. [This dataset][ticdata] encodes the complete set of possible board configurations at the end of tic- tac-toe games, where "x" is assumed to have played first. The target concept is "win for x" (i.e., true when "x" has one of 8 possible ways to create a "three-in-a-row"). Interestingly, this raw database gives a stripped-down decision tree algorithm (e.g., ID3) fits. However, the rule-based CN2 algorithm, the simple IB1 instance-based learning algorithm, and the CITRE feature-constructing decision tree algorithm perform well on it.

## Selection of algorithms
Due to the fact that we have the usual problem of Binary Classification, the standard algorithms of machine learning was implemented:
- Support Vector Classification
- Logistic Regression
- KNeighbors Classification
- Random Forest Classification
- Gradient Boosting Classification



[ticdata]: <https://archive.ics.uci.edu/ml/datasets/Tic-Tac-Toe+Endgame>
