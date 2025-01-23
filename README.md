# F1
dataset link: https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020

Hello, this notebook aims to analyse the performance of drivers specifically in the 2023 season. It compares the drivers based on a formula:

RR = Adjusted Race Results
CQP = Car Qualifying Performance
Driver Skill (DS) = ARR/CQP

for eg. 
Driver finished 3rd 
Car was the 4th best car on average based on qualifying results for that weekend

- ARR = 20 / 3 = 6.67
- CQP = 4
- DS = 6.67 / 4 = 1.67

if DS > 1, means the driver has outperformed the car
if DS ~ 1, means the driver is performing at the car level
if DS < 1, means the driver is underperforming

things to note: 
the way to calculate the qualifying results is the average of all the qualifying results of the team's 2 drivers that weekend. 

for eg. max verstappen completed q3 that weekend and perez only managed q2, the average is between the q1, q2, q3 of Verstappen and the q1 and q2 timings of perez. average timing = avg(q1Verstappen,q2Verstappen,q3Verstappen,q1Perez,q2Perez)

However, there are many considerations that this formula does not consider, hence the subjective nature of sport.

**Conclusion:** During this project I learnt about joins in python and applied what I learnt in my Data Management module in SQL. It made me more comfortable with Pandas and Numpy.
