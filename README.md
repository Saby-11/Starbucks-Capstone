# Starbucks Capstone Project
## Introduction:
This project is part of the Udacity Capstone Challenge and the given data set contains simulated data that mimics customer behaviour on the Starbucks rewards mobile app.

## Project Motivation:
This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks.

I chose this project to understand the success rate of offers being sent and analysis on offers through addressing the following questions:

1. To determine the elements that constitute whether a customer will respond to an offer
2. To explore whether a user would take up an offer or are their any common characteristics on the customers who take the offer.

## Installations:
1. Python 3.6+
2. pandas
3. numpy
4. matplotlib
5. sklearn
6. time
7. json

## File Description:
There is a notebook available to showcase work related to the above questions and wrangling process. There are 3 data files used to address the above questions-

1. portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
2. profile.json - demographic data for each customer
3. transcript.json - records for transactions, offers received, offers viewed, and offers completed

## Conclusion
1. I saw that for all the models the top 3 variables were all same that included: Membership tenure, Income and Age.
2. The decision to use 3 separate models to predict the effectiveness of each offer type ended up with good accuracy for the Bogo and discount models (82.83% for Bogo and 87.35% for discount), while slightly less accurate performance for informational offers (75.3%). 

A detailed analysis of the findings can be found in this [blog](https://medium.com/@saurabh11iiitu/exploring-ways-to-send-starbucks-offers-in-an-effective-way-3d9afb0ad997)

## Acknowledgement:
1. Dataset provided by [Starbucks](www.starbucks.com).
2. [Udacity](www.udacity.com) for briniging this opportunity as part of their amazing Data Scientist Nanodegree.
