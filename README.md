# Billing-Assignment
Objective:
To calculate monthly billing amounts for items like desks and parking spaces, based on their usage dates and rates.

Approach:
I used Python with the datetime and dateutil libraries.
Parsed item data to find overlap with the target month.
Prorated the billing based on the number of active days.
Summed all the individual prorated amounts for a total monthly revenue.

Formula:
Prorated Amount = (rate × quantity) × (active days / total days in month)

Result:
Total billing revenue for November 2024 is: ₹1,07,960.00

Tools Used:
VS Code
Python
Jupyter Notebook (.ipynb)
dateutil
