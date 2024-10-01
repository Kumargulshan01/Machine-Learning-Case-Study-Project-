# Machine-Learning-Case-Study-Project-
**Project Name** - Retail Sales Prediction
**Project Type** - Regression
# Project Summary -
Rossmann, a retail chain, operates an extensive network of over 3,000 pharmacies across seven European countries. Presently, the store managers at Rossmann face the challenge of forecasting their daily sales for the upcoming six weeks. Numerous factors such as promotions, competition, school and state holidays, seasonal variations, and local demographics affect the sales performance of each store. Given the diverse circumstances of individual managers, the accuracy of sales predictions tends to vary significantly.

# Problem Statement
We have access to historical sales data from 1,115 Rossmann stores. Our objective is to predict the "Sales" column for the test set. It's worth noting that some stores in the dataset were temporarily closed due to renovation work.

# Data Description
The dataset includes two main files:

Rossmann Stores Data.csv: This file contains historical data, including sales information.

store.csv: This file provides supplemental details about the stores. Data Fields:

Id: An identifier representing a combination of store and date within the test set. Store: A unique identifier for each store.

Sales: The turnover for a particular day (this is the target variable for prediction).

Customers: The number of customers on a given day.

Open: An indicator of whether the store was open (0 = closed, 1 = open).

StateHoliday: Indicates a state holiday; typically, stores are closed on these days. Types include a = public holiday, b = Easter holiday, c = Christmas, 0 = None.

SchoolHoliday: Indicates if the store was affected by the closure of public schools on that date.

StoreType: Differentiates between four store models: a, b, c, d.

Assortment: Describes the assortment level: a = basic, b = extra, c = extended.

CompetitionDistance: The distance in meters to the nearest competitor store.

CompetitionOpenSince[Month/Year]: Approximate year and month when the nearest competitor store opened.

Promo: Indicates whether a store is running a promotion on that day.

Promo2: Indicates whether the store is participating in a continuing and consecutive promotion (0 = not participating, 1 = participating).

Promo2Since[Year/Week]: Describes the year and calendar week when the store started participating in Promo2.

PromoInterval: Describes the consecutive intervals when Promo2 is initiated, listing the months the promotion begins anew. For example, "Feb,May,Aug,Nov" indicates that the promotion restarts in February, May, August, and November of any given year for that store.
