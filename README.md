# Cluster-Analysis-K-means-HAC-and-Decision-Tree-Induction-algorithm
## Problem:
Solving a mystery in history using Machine Learning with R: who wrote the disputed essays in the Federalist Papers, Hamilton or Madison?

Cluster Analysis and Decision Tree algorithm to solve a mystery in history: who wrote the disputed essays, Hamilton or Madison?
### 1. About the Federalist Papers
Quote from the Library of Congress http://www.loc.gov/rr/program/bib/ourdocs/federalist.html
The Federalist Papers were a series of eighty-five essays urging the citizens of New York to ratify the new
United States Constitution. Written by Alexander Hamilton, James Madison, and John Jay, the essays
originally appeared anonymously in New York newspapers in 1787 and 1788 under the pen name “Publius.”
A bound edition of the essays was first published in 1788, but it was not until the 1818 edition published by
the printer Jacob Gideon that the authors of each essay were identified by name. The Federalist Papers are
considered one of the most important sources for interpreting and understanding the original intent of the
Constitution.
### 2. About the disputed authorship
The original essays can be downloaded from the Library of Congress. http://thomas.loc.gov/home/histdox/
fedpapers.html
In the author column, you will find 74 essays with identified authors: 51 essays written by Hamilton, 15 by
Madison, 3 by Hamilton and Madison, 5 by Jay. The remaining 11 essays, however, is authored by “Hamilton
or Madison”. These are the famous essays with disputed authorship. Hamilton wrote to claim the authorship
before he was killed in a duel. Later Madison also claimed authorship. Historians were trying to find out
which one was the real author.
### 3. Computational approach for authorship attribution
In 1960s, statistician Mosteller and Wallace analyzed the frequency distributions of common function words
in the Federalist Papers, and drew their conclusions. This is a pioneering work on using mathematical
approaches for authorship attribution.
Nowadays, authorship attribution has become a classic problem in the data mining field, with applications in
forensics (e.g. deception detection), and information organization.

This is an attempt to solving this mystery using clustering algorithms (k-Means and HAC) and decision
tree induction algorithm.

## Results:
### Decision tree:
![Decision tree](https://drive.google.com/open?id=1I7bMYRdqdDHOWcTk2KvzzsUbdL0TTQhT)
![Decision tree] (https://drive.google.com/open?id=1GBKNduYl3869bK1d0QH6C0-_-xTm58h0)
### Kmeans:
![K-Means Plot] (https://drive.google.com/open?id=1Xflt4th_-mH3XX1so_UwL4y_Ce_aXvpL)
![K-Means Results] (https://drive.google.com/open?id=1vcD5CK33VhQkWt-2dyIdBdOcwqkk5puc)

#### It can be seen from the Decision tree models that all the disputed essay work was predicted to be done by Madison. And it can be seen in the table that k-means estimated the same and HAC produced the same result. Hence all algorithms concluded the same result.


