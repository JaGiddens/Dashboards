# Dashboards
Airbag Deployment Failure Analysis

Question: Which vehicles and crash conditions are most associated with unexpected airbag non-deployment?

Key Finding: 8.3% of crashes where our XGBoost model predicted airbag deployment resulted in failure. High-speed crashes deployed airbags 2–3× more often than non-high-speed crashes at every injury severity level. Among passenger vehicle makes with sufficient data, Audi and Jeep showed the highest failure rates (84%+), while Acura and Infiniti performed best (~74%).

Tools: Python · Pandas · Scikit-learn · XGBoost · Chart.js

Data: NHTSA Fatality Analysis Reporting System (FARS) 2023 — 36,470 crash records

Team Members: Jada Giddens, Austin Dinh, Tyler Yu


[Airbag Deployment Failure Analysis.pdf](https://github.com/user-attachments/files/25545212/Airbag.Deployment.Failure.Analysis.pdf)
