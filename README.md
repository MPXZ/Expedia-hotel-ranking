# Background: Expedia-hotel-ranking
train a model that learns to rank properties. Hotels.com travellers provide their trip information, like destination, holiday dates and number of people in the search. Search engine then returns a list of properties, ranked by their relevance to that traveller.

# Data description
1. A data set with travel information augmented by some features, including search-level features like booking window (length of time between booking the trip and taking it), and property-level features, like the country the property is in. 
2. The label in this data set is booking_bool, indicating whether this property was the one that was booked by the customer.

# Goal
To predict the score for each property and searchId, higher score means the property is most likely to be taken by a particular search ID

# PDF Content
### Loading data and package
### Exploration data analysis
1. Country analysis
2. Check-in and out date analysis
3. Hotel analysis
4. Price analysis
### Clean data and feature engineering
1. Categorical data
2. Numerical data
### Machine learning model 
1. Imbalanced dataset 
2. XGBoost
3. Entity embedding neural network
