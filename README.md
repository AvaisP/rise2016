<!DOCTYPE html>
<html>
<title>Fintech Webapp</title>

<xmp theme="united" style="display:none;">
# README.md

## Barclays Rise Hackathon 2016

A prototype of a Banking Portal for Corporate Treasurers providing visualizations of data models and aggregations of various bank accounts across different economies. Built with Django and Javascript, leveraging naive Bayes classification and Tradeoff Analytics using IBM Watson.

Awarded the Best implementation of the Envestnet Yodlee Bank Data Aggregator API.

## Features

We have developed a platform for the Corporate Treasurer that streamlines the visualization of all aspects of the company data.

We have added and used a currency pattern prediction algorithm that uses machine learning to predict trends in currencies.

![Hackathon Screenshot 1](res/hack1.png?raw=true "Minimum Balance")
![Hackathon Screenshot 2](res/hack2.png?raw=true "Currency Prediction Sample")

## Minimum Balance

Starting with the calculation of minimum balances, running a linear regression to predict the future minimum balance estimations and accordingly generate transfer alerts and send an SMS to the registered phone number using the Twilio API. It would also generate trasfer alerts based on currency trends in order to avoid devaluation of assets.

![Hackathon Screenshot 3](res/hack3.png?raw=true "Transaction Data")
![Hackathon Screenshot 4](res/hack4.png?raw=true "Tradeoff Analytics")

## Transaction Analysis 

Apart from this, we use the transactions, investment and other customer data from Yodlee in order to load the investment portfolio and use the IBM Watson API in order to generate a tradeoff-based credit risk analysis, thus predicting the most profitable investment.

## Authentication

Apart from this we have other standard features such as Registration, Login, viewing the User Profile and so on. 
Finally, we also have a pie chart depicting which transactions are non-essential or could be eliminated in case the account balance is falling below the minimum levels.


# Problem Statement

We approached the problem from one particular angle, with regards to the Corporate Treasurer and made it easier for him to visualize his data. Furthermore, we developed methods that would prove useful to not only him, but also others working wit the same account, be it the Account Managers or Executives.

Our predictive algorithms help enable quick and efficient decision-making thus effectively addressing the problem statement.

Our predictions and the enrichment of data sets that we have utilised make our predictions accurate. The variation in trends is extremely simple to visualize by means of graphs and charts as we have depicted it.

Our product would scale well due to the fact that we have a number of Robust APIs available and in spite of stubbed data, we would be perfectly comfortable using a time-series based approach for streaming data. 

</xmp>

<script src="http://strapdownjs.com/v/0.2/strapdown.js"></script>
</html>