# PlayQ-A-B-Testing-challenge

PlayQ is a rapidly growing global entertainment and technology company delivering high-quality mobile titles and innovative game development solutions to a worldwide audience. Our games have been downloaded more than 60 million times across the globe, with millions of users playing every day! 

PlayQ has launched new feature in single-player mobile game.The feature was made available to a sample of players as a part of an A/B experiment from 2018-01-17 to 2018-01-24.

The overall goal of the feature was to increase player engagement with the game and revenue.

The dataset ​should​ include one record for each player per day that they logged in to the game
during the week that the feature was active. The fields are defined as follows:
● user_id​: a unique identifier for each player
● feature_enabled​: a Boolean value that flags whether the player was in the sample of
players who could engage with the feature (0 = not selected; 1 = selected)
● experiment_selected_date​: the date on which the player was selected into the
experiment
● event_date​: the date on which the player logged in to the game
● games_played​: the number of games played
● revenue​: the revenue generated in US dollars

Conclusion
By analysing a few KPIs such as conversion rate, average game played and average revenue in the test results, we can conclude the following points:

● The treatment increased the conversion rate revenue and games played by 11% and 126% respectively.
● The treatment increased the overall average number of revenue during the period of abtest
● The treatment increased the overall retentation of users
● The overall test is successful since the treatment did confidently increse the conversion rate. However, the new treatment will not showing significant increase in customer engagement e.g. average game rounds/player/day
For further investigation, we may want to monitor group B for a bit longer time and study player loyalty and player behavior after conversion.

The introduced treatment might be:

● Increase of difficulty so that players get more frustrated and played less and bought more boosters/lives
● Increase of waiting time before getting new lives, or getting less lives per time, since players are playing less frequently, while some are buying more lives.
