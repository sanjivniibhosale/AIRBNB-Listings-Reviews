Airbnb Listings and Reviews EDA Project
Overview
This project involves performing Exploratory Data Analysis (EDA) on Airbnb listings and reviews data. The datasets are sourced from Kaggle and were contributed by Mysar Ahmad Bhat. The primary objective is to extract meaningful insights and patterns from the data to understand various aspects of Airbnb listings.
Datasets
Listings Data
The listings data contains the following columns:
•	listing_id
•	name
•	host_id
•	host_since
•	host_location
•	host_response_time
•	host_response_rate
•	host_acceptance_rate
•	host_is_superhost
•	host_total_listings_count
•	host_has_profile_pic
•	host_identity_verified
•	neighbourhood
•	district
•	city
•	latitude
•	longitude
•	property_type
•	room_type
•	accommodates
•	bedrooms
•	amenities
•	price
•	minimum_nights
•	maximum_nights
•	review_scores_rating
•	review_scores_accuracy
•	review_scores_cleanliness
•	review_scores_checkin
•	review_scores_communication
•	review_scores_location
•	review_scores_value
•	instant_bookable
Reviews Data
The reviews data contains the following columns:
•	listing_id
•	review_id
•	date
•	reviewer_id
Libraries Used
The following Python libraries were used for the EDA:
•	numpy
•	pandas
•	collections.Counter
•	matplotlib.pyplot
•	seaborn
•	sklearn.cluster.KMeans
•	sklearn.preprocessing.StandardScaler
EDA Scenarios and Insights
The EDA was conducted through the following scenarios to derive insights from the data:
Scenario 1: Distribution of Listing Prices
Analyzed the distribution of prices for Airbnb listings to understand the pricing landscape and identify any outliers.
Scenario 2: Room Type Analysis
Investigated the different room types available in the listings to determine the most and least common types.
Scenario 3: Number of Reviews Over Time
Examined the number of reviews received over time to identify trends and peak periods for reviews.
Scenario 4: Clustering of Listings Based on Prices and Locations
Used clustering techniques to group listings based on their prices and geographic locations, providing insights into price segmentation across different areas.
Scenario 5: Common Types of Airbnb Listings
Identified the most common types of Airbnb listings to understand the predominant types of accommodations offered.
Scenario 6: Price Variation Across Neighborhoods or Regions
Explored how listing prices vary across different neighborhoods or regions to highlight areas with higher or lower price points.
Scenario 7: Key Factors Influencing Listing Prices
Investigated various factors that influence listing prices, such as location, property type, and amenities.
Scenario 8: Correlation Between Listing Characteristics and Review Scores
Analyzed the correlation between listing characteristics (e.g., number of bedrooms, amenities) and review scores to determine factors that contribute to higher ratings.
Scenario 9: Common Amenities Offered by Airbnb Hosts
Examined the amenities offered by hosts to identify the most commonly provided amenities and those that are less frequent.
Conclusion
The EDA on the Airbnb listings and reviews data provided valuable insights into pricing trends, room types, review patterns, clustering of listings, and key factors influencing prices and review scores. This analysis can help hosts optimize their listings and potential guests make informed decisions.


