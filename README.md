# Titanic-Survival-Prediction

## Overview

The data has been split into two groups:

<ul>
  <li>training set (train.csv)</li>
  <li>test set (test.csv)</li>
</ul>

<p>The training set should be used to build your machine learning models. For the training set, the outcome (also known as the “ground truth”) will be provided for each passenger. Your model will be based on “features” like passengers’ gender and class. You can also use feature engineering to create new features.</p>
<p>The test set should be used to see how well your model performs on unseen data. For the test set, we do not provide the ground truth for each passenger. It is your job to predict these outcomes. For each passenger in the test set, use the model you trained to predict whether or not they survived the sinking of the Titanic.</p>

## Data Dictionary

<table>
  <tr>
    <td><b>Variable</b></td>
    <td><b>Definition</b></td>
    <td><b>Key</b></td>
  </tr>
  <tr>
    <td>survival</td>
    <td>Survival</td>
    <td>0 = No, 1 = Yes</td>
  </tr>
  <tr>
    <td>pclass</td>
    <td>Ticket class</td>
    <td>1 = 1st, 2 = 2nd, 3 = 3rd</td>
  </tr>
  <tr>
    <td>sex</td>
    <td>Sex</td>
  </tr>
  <tr>
    <td>Age</td>
    <td>Age in years</td>
  </tr>
  <tr>
    <td>sibsp</td> 	
    <td>no. of siblings / spouses aboard the Titanic</td>
  </tr>
  <tr>
    <td>parch</td>
    <td>no. of parents / children aboard the Titanic</td>
  </tr>
  <tr>
    <td>ticket</td>
    <td>Ticket number</td>
  </tr>
  <tr>
    <td>fare</td>
    <td>Passenger fare</td>
  </tr>
  <tr>
    <td>cabin</td>
    <td>Cabin number</td>
  </tr>
  <tr>
    <td>embarked</td>
    <td>Port of Embarkation</td>
    <td>C = Cherbourg, Q = Queenstown, S = Southampton</td>
  </tr>
</table>

## Variable Notes

<b>pclass</b>: A proxy for socio-economic status (SES)
<ol type='a'>
  <li>1st = Upper</li>
  <li>2nd = Middle</li>
  <li>3rd = Lower</li>
</ol>
<b>age</b>: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5 <br />

<b>sibsp</b>: The dataset defines family relations in this way...
<ol type='a'>
  <li>Sibling = brother, sister, stepbrother, stepsister</li>
  <li>Spouse = husband, wife (mistresses and fiancés were ignored)</li>
</ol>

<b>parch</b>: The dataset defines family relations in this way...
<ol type='a'>
  <li>Parent = mother, father</li>
  <li>Child = daughter, son, stepdaughter, stepson</li>
  <li>Some children travelled only with a nanny, therefore parch=0 for them.</li>
</ol>
