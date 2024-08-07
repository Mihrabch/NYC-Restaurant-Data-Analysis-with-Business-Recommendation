# NYC Restaurant Data Analysis

## Context
The number of restaurants in New York is increasing day by day. Lots of students and busy professionals rely on those restaurants due to their hectic lifestyles. Online food delivery service is a great option for them. It provides them with good food from their favorite restaurants. A food aggregator company FoodHub offers access to multiple restaurants through a single smartphone app.

The app allows the restaurants to receive a direct online order from a customer. The app assigns a delivery person from the company to pick up the order after it is confirmed by the restaurant. The delivery person then uses the map to reach the restaurant and waits for the food package. Once the food package is handed over to the delivery person, he/she confirms the pick-up in the app and travels to the customer's location to deliver the food. The delivery person confirms the drop-off in the app after delivering the food package to the customer. The customer can rate the order in the app. The food aggregator earns money by collecting a fixed margin of the delivery order from the restaurants.

## Objective
The food aggregator company has stored the data of the different orders made by the registered customers in their online portal. They want to analyze the data to get a fair idea about the demand of different restaurants which will help them in enhancing their customer experience. Suppose you are hired as a Data Scientist in this company and the Data Science team has shared some of the key questions that need to be answered. Perform the data analysis to find answers to these questions that will help the company to improve the business.

## Data Description
The data contains the different data related to a food order. The detailed data dictionary is given below.

## Data Dictionary
order_id: Unique ID of the order
customer_id: ID of the customer who ordered the food
restaurant_name: Name of the restaurant
cuisine_type: Cuisine ordered by the customer
cost_of_the_order: Cost of the order
day_of_the_week: Indicates whether the order is placed on a weekday or weekend (The weekday is from Monday to Friday and the weekend is Saturday and Sunday)
rating: Rating given by the customer out of 5
food_preparation_time: Time (in minutes) taken by the restaurant to prepare the food. This is calculated by taking the difference between the timestamps of the restaurant's order confirmation and the delivery person's pick-up confirmation.
delivery_time: Time (in minutes) taken by the delivery person to deliver the food package. This is calculated by taking the difference between the timestamps of the delivery person's pick-up confirmation and drop-off information.


## Conclusions:
1. Most Effective - Cost Variability: Southern cuisine is the most expensive, while Korean and Vietnamese are the least expensive, highlighting significant pricing differences.

2. Moderately Effective - Preparation Times: Thai cuisine has the longest preparation time, and Korean cuisine has the shortest, indicating variability in preparation demands.

3. Less Effective - Consistent Preparation: Preparation times are stable across weekdays and weekends for most cuisines, showing minimal variability.

4. Effective - Ratings and Delivery: Higher ratings are linked to longer delivery times and higher costs, suggesting that customers value quality over speed.

5. Most Popular Restaurant: Shake Shack, The Meatball Shop, Blue Ribbon Sushi, and Blue Ribbon Fried Chicken meet promotional criteria with high ratings and rating counts over 50.

## Recommendations:
1. Most Effective - Promotions: Offer promotions for mid-priced cuisines like Mexican and Indian; highlight affordable options like Korean and Vietnamese.

2. Moderately Effective - Efficiency: Streamline preparation for time-consuming cuisines like Thai; promote quick-prep options during peak hours.

3. Effective - Quality Focus: Maintain high quality for top-rated cuisines; use feedback to improve lower-rated ones.

4. Less Effective - Marketing: Emphasize consistent pricing and preparation times for Mediterranean and Chinese cuisines; leverage high ratings in promotions.

5. Promotional Offers: Focus promotional offers on popular restaurants like Shake Shack, The Meatball Shop, Blue Ribbon Sushi, and Blue Ribbon Fried Chicken to attract more customers.

