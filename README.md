# SIMULATION-OF-MEAN-AND-VARIANCE-USING-SCILAB-T1-C12-EVEN

---

## AIM:
To write a program for mean, variance and cross correlation in SCILAB and verify the output.

---

## EQUIPMENTS NEEDED:
- Computer with i3 Processor  
- SCILAB  

---

## ALGORITHM:
- Define the Function: Specify the function to simulate  
- Generate Sample Points: Decide range and number of points  
- Evaluate the Function: Compute values  
- Compute Mean, Variance and Cross Correlation  
- Display Results  

---

## PROCEDURE:
1. Refer Algorithms and write code for the experiment  
2. Open SCILAB in System  
3. Type your code in New Editor  
4. Save the file  
5. Execute the code  
6. If any error, correct it and execute again  
7. Verify the generated results  

---

## PROGRAM
```scilab
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

## OUTPUT GRAPH:
<img width="176" height="285" src="https://github.com/user-attachments/assets/45a1a072-3537-4d1c-bd61-36e9bf8e404d" />

---

## RESULT:
Thus the mean and variance were computed using SCILAB and the results were verified successfully.
