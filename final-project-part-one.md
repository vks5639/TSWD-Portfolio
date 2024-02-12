| [home page](https://vks5639.github.io/My-Portfolio/) | [visualizing debt](dataviz) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |


# Outline

## Summary

Growing up I realised the long-term benefits and future of real estate. I always wanted to create something of my own. Reading books like Rich Dad Poor Dad by Robert Kiyosaki, a Japanese-American businessman and author
further piqued my interest in how to be financially independent and make money work for you rather than working for money (Kiyosaki, R. T. 2017). This led me to think further about how to make investments to purchase plots, and build restaurants, and apartments.

Through this project, I will dive in through the problems and bottlenecks one might face when opening a restaurant. With data readily available, I will gather insights on who the competitors are, and compare the metrics of top cuisines, ratings, review counts, price, etc. In easy words, how can I create a business model to open a restaurant in an area of choice?
 
## Project Structure

The book Good Charts, (Berinato, 2016, p. 199) mentions, "Any story can be told in multiple ways, but a good way to start is to break the idea into three basic dramatic parts: setup, conflict, and resolution." The major elements of my story will be structured based on the following:

### Setup: New restaurants involve selecting a location, managing costs, analyzing competitors, and comparing ratings and reviews.

### Conflict: Lack of statistical data insights creates challenges of unexpected costs, delays, stronger competition, and closure of restaurants.

### Resolution: Strategic planning optimizes location benefits, manages financial resources, gains edge over competitors, and gains better reviews and ratings.

The above structure will help me understand the existing problem and with the availability of data, I can further gain insights on which is the best way ahead to successfully build a restaurant. I will be informed of mistakes in the business models of existing restaurants which will help me avoid those when I create a business model of my own.

### User Story
As an individual, I want to gather data insights on restaurants, so that I can build a restaurant of my own.

Creating a solid business model will help me avoid risks and failures in my investments in real estate.

![img1](https://i.imgur.com/DebCGJX.jpeg) 


# Initial sketches

I will be creating an interactive map that will provide all the restaurants in the location selected to open a restaurant. For every competitor restaurant, I will detail the parameters like ratings, reviews, price, the best-sold dish, etc. This will help me understand that if I want to gain an edge over my competitor, which pitfalls must I avoid? For example, if a location has a Mexican restaurant, with a large review count, and a good rating, the chances are there are more Mexicans in the area or people in the area love Mexican food.

I will also create separate bar charts to quickly understand restaurants and their rankings for each parameter. I will sort them from best to worst. To enhance data visualization, I will then be creating a heat map to sort all the restaurants in the location

![img1](https://i.imgur.com/JLTR3T2.png)

![img1](https://i.imgur.com/nGVrPAQ.png)



# The Data

I will be scraping data from public repositories. I will be using a publicly available data repository Yelp API. This will have data on restaurant location, cuisine type, ratings, reviews, price, and review counts. Based on the above parameters, I can analyze the conflicts, I might have opening a new restaurant. I can filter the data to make concise data visualizations which will help me make better decisions.

I will be using open source platform, PostmanAPI to grab the JSON data of the restaurant parameters and convert it into csv file. I will use Python libraries like Numpy and Panda to clean the data. Finally, I will be using Tableau to create visualization which will act as a reference to create business models.

1. Name: Yelp Fusion API                               
2. URL: https://api.yelp.com/v3/businesses/search                                                                    
3. Description: Public data repository with data on restaurant location, cuisine type, ratings, reviews, price, and review counts 


# Method and medium
With a clear understanding of the project structure, availability of data, and initial sketches, I will use Shorthand and Tableau to create an attractive visualization that will not help only me but anyone who is looking to create a business model or improve an existing business model to open a restaurant.

# References

1. Kiyosaki, R. T. (2017). Rich dad, poor dad. Plata Publishing.
2. Berinato, Scott. (2016). Good charts : the HBR guide to making smarter, more persuasive data visualization . Boston: Harvard Business Review.


