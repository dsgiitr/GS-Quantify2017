# GS-Quantify2017
### Winner's Solution for Predicting Garbage Collector Invocation

### Team Name: Analytics_rangers

### Team Members: Roopkishor Singh| Harsh Singhal| Gaurav Jindal

## Problem Statement:

### Garbage Collector Invocation 

Overall objective of this challenge is to use provided data to predict when Garbage Collector gets triggered,
and the amount of free memory available.

#### Background

Goldman Sachs is building a customized search engine for an internal text dataset. The search engine is launched
on a container with a maximum memory limit. It takes some initial resources to launch the search engine on the container.
Once the search engine is initialized, every time a search query is passed, it requests some additional resources 
for the search query to be served. The amount of resources requested by the search query would be a function of the
frequency of the query keyword in the text corpus.

#### Constraints

The only constraint for the problem is that the sum of the used memory and the free memory would never exceed the 
total container memory which is limited to 9 GB.

#### Points to be Noted

- The accuracy of the gcRun prediction which would be evaluated based on the precision and recall of the model.
More weightage would be given to the recall of the model as compared to the precision. Also, if the candidates
are able to predict the GC trigger in the vicinity of the actual GC trigger in the test set,that would be counted 
in the calculation of the true positives in precision and recall calculation

- The RMSE error for the free memory prediction at each step



