# Analysis-of-airbnb-in-Washington-with-Tableau-Excel

![image](https://user-images.githubusercontent.com/91364462/218611011-fdf07731-8ba0-4bbb-89ed-434633fa7135.png)

**Project Description:** My friend is interested in starting an airbnb business in Washington. He asked me to assist him with the analysis of the airbnbs in the state to understand the average price of bedrooms, the revenue that could be expected, the time of the year with high revenue, and finally, he asked to know the locations in Washington with the highest airbnb prices. I needed to first obtain information about airbnbs in Washington in order to fulfil these requests for my friend, and fortunately I was able to do so from this [website](http://insideairbnb.com/get-the-data/). 

**About the dataset:** This dataset, which consists of just a single spreadsheets, was first cleaned and prepared by separating the single sheet that contained information about listings, reviews, and date information into separate sheets for straightforward analysis, this data can be found [here](https://www.kaggle.com/datasets/alexanderfreberg/airbnb-listings-2016-dataset). The sheets include:

- Listings: The information in this sheet includes information about the location, address, listing url, name of the airbnb, name of the host, year the airbnb was first listed, room types and their capacities, how responsive the hosts are, number of bedrooms, amenities present in the airbnb, price, and many other details that were not necessarily useful for the analysis. This sheet is the largest dataset with 92 columns and 3816 rows. 

- Reviews: There were only six columns on this sheet, and they included the reviewer's name, the date the review was submitted, the review Id, the listing Id, the reviewer's ID, and any general remarks they had. There were 84,850 reviews on this sheet.

- Calender: With only four columns and over one million rows, this is the largest of them all. This sheet's details include: 


|Column Name| Column Description |
|------------|--------------------|
|`listing id`| The identifaction number of each listing. This is the key used in seprating the dataset into separate sheet|
|`date`| Date the listing were last updated |
| `Price`| Price of airbnb with respect to the data |
| `availability` | Indicates if the airbnb were booked or not at a particular time of the year |

**Summary of findings**
- The average cost of an Airbnb increases with the number of bedrooms.
- Due to the fact that June is peak summer season and December is peak holiday season, the income from AirBnB peaks in these months.
- Central Business District and Capital Hill has the most expensive airbnbs while crown hill has the cheapest airbnbs



