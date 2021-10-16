#### *API's_HW_4*
# Financial Planning

This file accompanies the new financial analysis tools being provided to Large Credit Union customer. 

## Goal of This Notebook 
The goal of these analysis tools is to provide your credit union members with the ability to assess their monthly personal finances, and plan for their retirement. 

### Part I - Personal Financial Planner

With this planner, your members can input their cryptocurrency holdings, and their stocks and bonds portfolio, and review their current portfolio value. This planner utilizes the Alpaca API to gain access to up-to-the-minute currency values. The final step provides a comparison between current savings portfolio value and goal savings amount (based on monthly income), to provide your members with that important feedback about their financial health.

### Part II - Retirement Planning Tood

This retirement planning tool again uses the Alpaca API to get historical prices of the member's stock and bond holdings, and then utilizes a monte carlo simulation to project a range of likely values after the 30-year holding period. It also explores options for a shorter holding period (early retirement). 

# Technical Notes

## Libraries
This Jupyter Lab notebook utilizes the following libraries:

os

Pandas

Numpy

dotenv

JSON

Pathlib

Alpaca Trade API

MCForecastTools

matplotlib

## Data Inputs

Besides the elements related to those libraries, additional data to be input by the user includes their currency holdings, their stocks and bonds amounts, and their monthly income amounts.  

# Acknowledgements

I would like to first acknowledge the guidance and teaching of our FinTech Boot Camp Instructor, Garth Mortensen, our TA, Alejandro Esquivel, and out Student Success Manager, Angelica Baraona. The Monte Carlo simulation is run on the MCSimulation within the MCForecastTools toolkit, much appreciated. Also would like to mention Stack Overflow and the tech website collective in general. Regarding API's I found useful nuggets on the Red Hat site and the Alpaca site itself.  Finally, some of the main books I used for background during this boot camp phase were "Continuous API Management - Making the Right Decisions in an Evolving Landscape" by Medjaoui, Wilde, Mitra and Amundsen; and "API's, A Strategy Guide" by Jacobson, Brail and Woods. 
