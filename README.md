## Background
The Iris flower dataset is a classic classification dataset ideal for beginners. The data uses morphometric measurements of petals and sepals to distinguish between Iris species.
A good model should be able to differentiate three Iris species using simple, easy-to-measure physical features.

## Problem Description
Participants are asked to develop a multi-class classification model that predicts Iris species from four morphological features.

## About the Dataset

### Data collection
This Iris dataset contains measurements of sepal length, sepal width, petal length, and petal width for each flower. The dataset is designed to be easy to understand and well-suited for introductory classification experiments.

### Column Description
This Iris dataset contains measurements of sepal length, sepal width, petal length, and petal width for each flower. The dataset is designed to be easy to understand and well-suited for introductory classification experiments.
<table>
  <tr>
    <td><b>Column Name</b></td>
    <td><b>Data Type</b></td>
    <td><b>Description</b></td>
  </tr>
  <tr>
    <td>id</td>
    <td>Integer</td>
    <td>Unique identifier for each observation</td>
  </tr>
  <tr>
    <td>sepal_length</td>
    <td>Float</td>
    <td>Sepal length in centimeters</td>
  </tr>
  <tr>
    <td>sepal_width</td>
    <td>Float</td>
    <td>Sepal width in centimeters</td>
  </tr>
  <tr>
    <td>petal_length</td>
    <td>Float</td>
    <td>Petal length in centimeters</td>
  </tr>
  <tr>
    <td>petal_width</td>
    <td>Float</td>
    <td>Petal width in centimeters</td>
  </tr>
  <tr>
    <td>species</td>
    <td>String</td>
    <td>Iris species (setosa, versicolor, virginica) - TARGET</td>
  </tr>
</table>

### Dataset Information
+ Training rows: 59
+ Testing rows: 18
+ Number of features: 4
+ Target: species (multi-class classification, 3 classes)

## Accuracy
Accuracy measures the percentage of correct predictions out of all predictions made.

### Formula
$$\text{Accuracy} = \frac{\text{Number of Correct Predictions}}{\text{Total Predictions}}$$

Or:

$$\text{Accuracy} = \frac{TP+TN}{TP+TN+FP+FN}$$

Where:

+ $TP$ = True Positive (correct positive prediction)
+ $TN$ = True Negative (correct negative prediction)
+ $FP$ = False Positive (incorrect positive prediction)
+ $FN$ = False Negative (incorrect negative prediction)
