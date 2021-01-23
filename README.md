## Starbucks Challenge

This is the work for the Udacity Data Science Nanodegree Capstone.

### Prerequisites

python version 3.7.*

And the following Python packages:

* pandas
* numpy
* matplotlib
* seaborn
* sklearn

### Project Motivation

The goal of this project is to find which reward offers to sent to each customer that is enrolled in the Rewards Programs of Starbucks' Rewards App.
To achieve that we will cluster customers taking into account demographic and consumption data.

### Files Description
#### Data

**portfolio.json**
* id (string) - offer id
* offer_type (string) - type of offer
* difficulty (integer) - minimum required spend to complete an offer
* reward (integer) - reward given for completing an offer
* duration (integer) - time for offer to be open, in days
* channels (list of strings) - web, email, mobile and social.

**profile.json**
* age (integer) - age of the customer
* became_member_on (integer) - date when customer created an app account
* gender (string) - gender of the customer
* id (string) - customer id
* income (float) - customer's income

**transcript.json**
* event (string) - record description (transaction, offer received, offer viewed or offer completed)
* person (string) - customer id
* time (integer) - time in hours since start of test (t=0 is the beginning of the test)
* value (dictionary of strings) - either an offer id or transaction amount, depending on the record

#### Starbucks_Capstone.ipynb:
Contains all the code for this work.

### Results

The discussion of the results, conclusions and future considerations can be found here: https://medium.com/@inessdra/how-can-marketing-campaigns-be-improved-at-starbucks-4377394a6218