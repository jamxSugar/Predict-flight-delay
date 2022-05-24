# Prediction-on-Airline-On-time-Performance

### Coursework of Predictive Model and Analysis

**Based on a [dataset](https://community.amstat.org/jointscsg-section/dataexpo/dataexpo2009) that consists of arrival and departure details from all the flights ✈ within the US domestic market for the year 2008, this project aims to extract valuable insights and build basic models to predict flight delays. **

Since flights cancellation were very rare, with only 633 out of 1936758 flights cancelled in the whole year, we build models to predict only flight delays and provide accuracy details. The model can help us figure out what makes an airline delay, and how to improve their air routes. 

To customize the dataset, we focus on the flights where the unique carrier code is ‘YV’. It represents Mesa Airlines. The customized data has 67063 flight details and 30 variables. In the preprocessing stage, we created new variables and filled the missing values. We split the dataset into train set and test set, and then build 4 different models to test their performance. Finally, we chose a best-performed model to predict delayed flights.

