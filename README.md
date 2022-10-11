# indian_restaurants
This is a data science project to locate the best Indian restaurants in New York. We can use this information to inform Indian families about the best place to stay in New York, where they will feel at home.
# Introduction
New York is one of the world's biggest, most diverse, and most exciting cities. With an estimated 8,336,817 residents in 2019 spread across 302.6 square miles (784 km2), it is also the most populous city in the United States. It has the highest population density in the country. 
The cultural, financial, and media hub of the world, New York City has a significant impact on business, entertainment, science, technology, education, politics, tourism, arts, fashion, and sports. It draws more tourists than any other city, with over 42 million yearly.
New York City comprises five boroughs: The Bronx, Brooklyn, Manhattan, Queens, and Staten Island. Each Borough is coextensive with a respective county of New York State, making New York City one of the U.S. municipalities in multiple counties. 
Many individuals are moving into New York every day. Selecting a nice restaurant in New York City for good local dishes will be highly valued. They have different categories of restaurants like Chinese, Indian, French, Arabic, and American.
One race that places a high value on culture and cuisine is the Indians. Indian cuisine draws heavily from its history. Some well-known spices, including turmeric, cardamom, black pepper, and mustard, were first harvested in India more than 5,000 years ago. It is a country where the cuisine varies greatly depending on where you are. Other elements, such as regionally unique fruits, vegetables, and herbs, affect the cooking.
 A national dish is a culinary creation closely linked to a specific nation. There are several reasons why it could be regarded as a national dish: It is a typical dish prepared in a country from various foods grown nearby. When people relocate to other parts of the world for work or vacation, they may feel the need to eat a specific food from home, but due to the new environment, this becomes impossible, causing them to constantly think of home.
Consider all the regional foods that are available in a particular area. This would assist in deciding where they could live and feel at home. This project aims to locate the top Indian restaurants in New York using data science. We can use this information to calculate the average Rating of Indian restaurants in New York if we can access their reviews, tips, and likes. Using the Foursquare API and calc joson, we scraped all their thoughts and other data from public sources.
# Data Gathering and Cleaning 
We would examine New York data that includes the geo-location of the boroughs and neighborhoods. The New York dataset at https://cocl.us provides information about people in New York from January to December 2011 and includes information about their boroughs and districts. The Second data source (Foursquare API) allows us to locate Indian restaurants by displaying their locations in each neighborhood, while the third Source for the data provides geospatial data to pinpoint the boundaries of the New York boroughs, allowing us to see them on a map and can be found at https://data.cityofnewyork.us/City-Government/Borough-Boundaries/tqmj-j8zm.
On my GitHub repository, all code and documentation will be accessible.
# Observation from Data science analysis
Using the same source, we will compare the outcomes of the best Indian Restaurant in 2020 with those of the best Indian Restaurants in 2022. This time frame spans two years. This will allow us to determine whether the same restaurants are still the best or if another restaurant has taken their place.
With our analysis, we would be using 3 significant factors, which are Ratings, Tips, and Likes, to determine the best Restaurant and location. We would also compare the report for 2020 and 2022 to determine if new restaurants are now dominating or if we still have the same restaurants as the best.
Fig 1, Sources ( https://en.wikipedia.org/wiki/Boroughs_of_New_York_City )
## Total Neighborhoods
           2020 Total Neighborhoods 					2022 Total Neighborhoods
Fig 2: New York City is composed of five boroughs: The Bronx, Brooklyn, Manhattan, Queens, and Staten Island; each Borough has its own sub-region called Neighborhoods. From 2020 to 2022, the queens still have the highest neighborhoods and the least neighborhoods in Manhattan. In total, we have 306 Neighborhoods.
## Total Restaurant 
           2020 Indian Restaurant in New York			 2022 Indian Restaurant in New York 
Fig 3: We have 144 Indian restaurants in New York as of 2020, and in 2022, we had an increase on 3 additional new Indian restaurants making it 147 in total. Queen has the highest number of Indian restaurants in the Borough in both years, followed by Manhattan, which has close to half of the numbers from Queens.
## Comparing 2020 Tips vs. 2022 Tips
                      	2020 Tips							2022 Tips
Fig 4:
Fig 4 shows the Restaurant with the Highest tips in 2020 vs. 2022. It indicates that Bhatti Indian Grill (https://www.bhattinyc.com/) has the highest bonuses in 2020, but in 2022 we have a new restaurant taking the spot: The Kati Roll Company (https://www.thekatirollcompany.com/ ) with over 95 tips making it the highest tipped Indian Restaurant in 2022. 
Both restaurants are in Manhattan, but in 2020 the Neighborhood was Gramercy. Now, we have Midtown as the location for best tipped. 
## Comparing 2020 Likes vs. 2022 Likes
                      	2020 Likes							2022 Likes
Fig 5:
Fig 5 shows the Restaurant with the Highest likes in 2020 vs. 2022. It indicates that Tamarind Tribeca (https://tamarindtribeca.com/) has the highest preferences in 2020, but in 2022 we have a new restaurant taking the spot: The Kati Roll Company (https://www.thekatirollcompany.com/) with over 235 likes making it the highest liked Indian Restaurant in 2022. 
Both restaurants are in Manhattan, but in 2020 the Neighborhood was Tribeca. Now, we have Midtown as the location for best liked. 
## Comparing 2020 Ratings vs. 2022 Ratings
                      	2020 Ratings							2022 Ratings
Fig 6:
Fig 6 shows that Bombay Bistros (https://bombaybistros.com/ ) has the highest Rating in 2020, but in 2022, we have a new restaurant taking the spot, which is Adda (https://www.addanyc.com/ ) with 9.1 ratings compared to the 9 rating of Bombay Bistros in 2020
Adda is located in Long Island City, Queens, and Bombay Bistros 2020, the highest rated, is located in Greenwich Village, Manhattan.


## Comparing 2020 Ratings vs. 2022 Ratings
                      	2020 Ratings							2022 Ratings
Fig 7:
From the fig7, with Ratings for 2020 and 2022, we can see the top 10 neighborhoods with the highest ratings. All the Neighborhoods in 2020 have declined in Rating. It's a totally new Neighborhood that is topping the charts now.
## Comparing 2020 Borough vs. 2022 Borough
                      	2020 Borough							2022 Borough
Fig 8:
From the fig8, Manhattan had the highest Rating in 2020 and still maintains the positions in 2022. The Bronx has slid down for Queens to take over in the third position in 2022.

# Conclusion 
We would be able to Identify that we have a total of five (5) boroughs in New york city with a total of 306 Neighborhoods. Queen, one of the boroughs, had the highest number of Indian restaurants. Floral park in Queens has the highest number of Indian restaurants from 2020 to 2022; it added a new restaurant in 2 years.
We could observe that the most tipped and liked. The Restaurant came from Manhattan, The Kati Roll Company (https://www.thekatirollcompany.com/), but the most rated comes from Queens, which is Adda (https://www.addanyc.com/).
From our top ten Neighborhood ratings, Long Island City is at the top and followed by bliss vile.
When we consider the general ratings, Manhattan has the highest for 2 years in a roll, followed by Brooklyn.
From the information, we could observe that Queens is a place an Indian family can feel close to home because it has more Restaurants for them to explore, and it also has one of the most rated restaurants,
But Manhattan is also a force to be reckoned with because it has average, the best Restaurant in New York City.
In other to select a location for an Indian family, I will suggest they pick Manhattan first and can also look at Queens.
Thank you.

