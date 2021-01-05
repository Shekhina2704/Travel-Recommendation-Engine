# GETAWAY: A Travel Recommendation Engine
#### OBJECTIVE:

To build a recommendation engine that suggests vacation spots to users.

#### DATA DESCRIPTION:

The dataset used consists of 1831 records and 30 columns, which can be split into 3 sections, namely:
1. User Details: User_Id, DOB,	Age,	Gender_code,	User_Locale,	User_locale_lang,	Preferred_cuisines, Previous_spending
2. Trip Details: Country_Code, Place (target variable),	Description, State, Theme,	Date,	Mode_of_transport, Cuisines, Number_of_travellers, Currency, Kind_of_stay, Price_range, Aggregate_rating, Rating_text, Votes, Suggested
3. Website Details: Clicks_on_booking, Frequency_of_visits_to_the_website, Ad_source, Time_spent, ps_lb, p_ub

A K-Nearest Neighbors Classifier was built to recommend tourist places to the user. The Python web framework, Flask, was used to develop the user interface.

