# MonteCarlo-Simulation-Loan-Amortization
Tutorial for conducting a monte carlo simulation against a loan amortization schedule. 
## **Summary**
This Python script is designed to simulate and visualize the potential lifetimes of a loan under various scenarios. It uses a **Monte Carlo method** to simulate thousands of potential **loan payoff** trajectories given varying probabilities of making extra payments or late payments.
## **Description**
The script works in the following steps:
It starts by defining parameters for a loan, such as the **principal amount**, **annual interest rate**, and **term in years**. These are then used to calculate the monthly payment using a standard loan amortization formula.
It then sets parameters for a Monte Carlo simulation, which includes the **number of simulations** to run and the probability of making **extra payments**. These extra payments are randomly applied to some months during the loan payoff period.
The script runs the Monte Carlo simulation, tracking the loan balance month by month and recording how many payments it takes to fully pay off the loan. Each simulation represents a possible **loan lifetime**.
The results are plotted in a **histogram**, showing the **distribution** of possible loan lifetimes.
The script then runs additional simulations for different probabilities of making extra payments and for different probabilities of making **late payments**. The impact of these scenarios on the loan lifetime is visualized in additional histograms.
For each scenario, it computes the **mean** and **standard deviation** of the loan lifetimes and reports the intervals within which **68%, 95%, and 99.7%** of loan lifetimes fall (according to the empirical rule in statistics).
## **Requirements**
To run this script, you need Python and several packages including **numpy**, **pandas**, **matplotlib**, **numpy-financial**, and **scipy**. You can install these packages using pip.
## **Usage**
Simply run the Python script to start the simulation and generate the plots. You can adjust the loan parameters and the parameters for the Monte Carlo simulations as needed.
## **Notes**
This script assumes that the interest is calculated on a monthly basis. If your loan uses a different compounding period, you will need to adjust the script accordingly. It provides a useful illustration of the potential impact of making extra payments on the speed of loan payoff and the potential consequences of making late payments.
For any questions or inquiries, please contact **support@pyfi.com** - Subject: Github Repo Q, MonteCarlo-Simulation-Loan-Amortization

For a full article walkthrough please visit > https://www.pyfi.com/blog < where you'll also be able to pick up a complimentary copy of the complete, Volume I text of our Machine Learning Edge Blueprint, a $49 value. This text will walk you through everything you need to get started coding Python for Finance
