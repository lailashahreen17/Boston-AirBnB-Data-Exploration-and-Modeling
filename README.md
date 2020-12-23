# Boston-AirBnB-Data-Exploration-and-Modeling
## Motivation
Since 2008, Airbnb has offerred their guests to travel in a more unique, personalized way and socialize with new people worldwide. As part of the Airbnb Inside initiative, Boston AirBnb dataset from [Kaggle](https://www.kaggle.com/airbnb/boston) is a great resource to be familiar with airbnb rental business for future host and also guest. To be exact, this is an opportunity to appear as a new host. As a part of Udacity Nanodegree Program ,our analysis represents methodical steps and rational reasoning to achieve that status. In the Jupyter notebook of this repository, we went through the CRISP-DM process in regard to the dataset and we gathered, assesd and cleaned them as neccssary for my desired analysis and model building.. These questions surely can bring insights to any host who is willing to host or customer who is willing to pay for a lovely stay around Boston city. Below are the questions we had in my mind.The [story]() is also told in medium.com.

1. Can you describe the vibe of each Boston neighborhood using listing descriptions?
2. What are the busiest times of the year to visit Boston? By how much do prices spike?
3. What factors affect the price of an AirBnB rental? Let's find out!

## Dataset
The following Airbnb activity is included in this Boston dataset:

* Listings, including full descriptions and average review score
* Reviews, including unique id for each reviewer and detailed comments
* Calendar, including listing id and the price and availability for that day

We have mainly used listings and calendar dataset.

## Libraries
1. Numpy
2. Pandas
3. Matplotlib pyplot
4. Sklearn
5. Seaborn
6. Math
7. Datetime
8. Wordcloud

## Results
1. Neighbourhood matters most.While neighborhood near Downtown are easy to access and a short walk to commute line(public transport), those are most wanted and also at the same time localities a bit far from city center brings quiet but active and diverse community with lower price.
2. Number of bedrooms and property type are also important for setting affordable price.
3. Availabily is not stable all year round. September to November is variying season. From January to September it remains pretty stable.
4. Few amenities such as wheelchair accessibilty, washer dryrer, TV, elevator add value to the property and pricing.
5. Reviews rating doesn't really impact on price variability.
6. The r squared value is 0.64 which explains the price variablity of 64% by our linear model which is not that bad. But there is still more room for improvement for better prediction.

## Acknowledgements
Special thanks to Kaggle and Udacity for the resources to explore this dataset.


