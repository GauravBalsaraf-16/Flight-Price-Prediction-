# Flight-Price-Prediction-
This dataset is for flight price prediction, including airline, source, destination, departure time, stops, class, duration, and days left. EDA was performed with data cleaning, visualization, and outlier detection. Models like Linear, Ridge, Lasso, Decision Tree, and Random Forest were used to predict prices based on these features.

**Dataset Description:**
This dataset contains 300,153 rows and 12 columns related to flight ticket pricing. It includes various features such as airline, flight duration, departure and arrival times, number of stops, and ticket class. The goal of this dataset is to build predictive models for estimating flight prices.

**Column Details:**
**Unnamed:** 0 (Integer) – Index column, not required for analysis.
**airline** (Object) – Name of the airline (e.g., SpiceJet, AirAsia, Vistara).
**flight** (Object) – Flight number associated with the airline.
**source_city** (Object) – The departure city of the flight.
**departure_time** (Object) – Time category of departure (Morning, Afternoon, Evening, etc.).
**stops** (Object) – Number of stops in the journey (e.g., zero, one, two).
**arrival_time** (Object) – Time category of arrival (Morning, Afternoon, Evening, etc.).
**destination_city** (Object) – The arrival city of the flight.
**class** (Object) – Ticket class (Economy, Business).
**duration** (Float) – Total duration of the flight in hours.
**days_left** (Integer) – Number of days left for departure.
**price** (Integer, Target Variable) – Flight ticket price.

**Exploratory Data Analysis (EDA) Performed:**
**Data Cleaning:** Removed unnecessary columns and ensured data consistency.
**Feature Engineering:** Extracted meaningful insights from categorical variables like departure time and stops.
**Data Visualization:** Plotted price distributions, duration impact on price, and variations based on airline and class.
**Outlier Detection:** Identified extreme values in flight duration and ticket prices.

**Machine Learning Models Used:**
**Linear Regression** – Used as a baseline model.
**Ridge and Lasso Regression** – Applied for better generalization and feature selection.
**Decision Tree and Random Forest Regressors** – Used for capturing non-linear relationships in price prediction.

This dataset serves as a foundation for flight price prediction, allowing analysis of pricing trends and travel patterns.
