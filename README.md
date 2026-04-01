# SIMULATION-OF-MEAN-AND-VARIANCE-USING-SCILAB-T1-C12-EVEN
AIM:

To write a program for mean, variance and cross correlation in SCILAB and verify the output.

---

#EQUIPMENTS NEEDED:

-Computer with i3 Processor

-SCILAB

---

ALGORITHM:

Define the Function: Specify the function you want to simulate. For example, f(x)=sin⁡(x)f(x)=sin(x) or any other function.
Generate Sample Points: Decide on the range and the number of sample points. Generate these sample points within the desired range.
Evaluate the Function: Compute the function values at each of these sample points.
Compute Mean, Variance and Cross Correlation: Use Scilab's functions to calculate the mean and variance of the computed function values.
Display Results: Output the computed mean variance and Cross Correlation

---
PROCEDURE:

1.Refer Algorithms and write code for the experiment.

2.Open SCILAB in System

3.Type your code in New Editor

4.Save the file

5.Execute the code If any Error, correct it in code and execute again

6.Verify the generated results

---
PROGRAM:
```
clc;
clear;

// Given data
X = [4 8 11 15 21];

// Number of elements
N = length(X);

// Calculate Mean
mean_value = sum(X) / N;

// Calculate Variance
variance_value = sum((X - mean_value).^2) / N;

// Display Results
disp("Mean = ");
disp(mean_value);

disp("Variance = ");
disp(variance_value);
```
---
OUTPUT GRAPH:
<img width="176" height="285" alt="{6AD0CE57-FDD1-4F3F-9CA2-2EA8164B7847}" src="https://github.com/user-attachments/assets/45a1a072-3537-4d1c-bd61-36e9bf8e404d" />


---
RESULT:
