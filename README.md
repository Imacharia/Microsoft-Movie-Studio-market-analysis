Microsoft's Movie Studio


This repository contains the code and materials for the Microsoft's Movie Studio project, part of the curriculum for the Data Science Career Track by Flatiron School.


Project Overview


Microsoft wants to enter the movie industry and they want to know what types of films have been successful at the box office. They have asked us to use exploratory data analysis to generate insights for their new movie studio. The goal of this project is to analyze the data from six different sources and provide Microsoft's head of the movie studio with actionable insights.


Business Undertanding


The business problem we are presented with is that Microsoft wants to enter the movie industry and create a new movie studio. However, they have limited knowledge about creating movies, and they need to understand the market demand and what types of films are currently successful at the box office.The stakeholders in this project include Microsoft executives, investors, and potential moviegoers who are interested in watching new and exciting movies.



To address this problem, the project must focus on identifying the types of movies that are currently doing well in the market and provide actionable insights to the head of Microsoft's new movie studio. The problem is to find the right strategy for Microsoft's new movie studio by understanding the audience's preferences and current market trends. By identifying the types of films that are currently successful, Microsoft can create a plan that aligns with the market's demand and attract potential customers.



Having a clear undertsnding of this will help Microsoft minimize risks, reduce costs, and increase the chances of success in a highly competitive market.Since the project will create value by assisting Microsoft shareholders make informed decisions by providing actionable insights about the type of films that are currently successful.



Overall, the project's goal is to assist Microsoft in creating a successful movie studio by identifying the types of films that are currently successful and translating these findings intoactionable insights that can guide decision-making.



From the currenlty provided data set of movies, we can explore what type of films are currently doing the best at the box office. some of the columns we might consider are genres, averagerating, domestic_gross, and worldwide_gross just to name a few.



First, we can group the movies by genres and calculate the average rating, domestic gross, and worldwide gross for each genre. This will give us an idea of which genres are more popular among audiences and are generating more revenue. We can use this information to identify the top genres that Microsoft's new movie studio should focus on.



Second, we can analyze the relationship between the movie rating and revenue. This analysis will give us insights into the impact of ratings on box office performance. It will help us understand whether higher-rated movies tend to perform better or not.



Finally, we can also look at the release date of the movies to see if there are any trends or patterns. This analysis can help us identify the best time to release a movie for maximum revenue.



Overall, by analyzing the provided dataset, we can provide actionable insights to Microsoft's new movie studio regarding what types of films to create.


Although there are more than the above mentioned analyzed relationships within this Notebook



Key Business Questions


The business questions that this project will address are:

1. What are the most popular movie genres in terms of audience ratings and revenue?
2. How does the rating of a movie affect its revenue at the box office?
3. What are the most successful movie studios in the industry, and how do they achieve success?
4. How does the budget of a movie affect its performance at the box office?
5. Are there any specific release dates or seasons that are more profitable for movie releases?


Data Understanding and Analysis


The data for this project was obtained from five different sources:

Box Office Mojo
IMDB
Rotten Tomatoes
TheMovieDB


The Numbers


Because the data was collected from various locations, the different files have different formats. Some are compressed CSV (comma-separated values) or TSV (tab-separated values) files that can be opened using spreadsheet software or pd.read_csv, while the data from IMDB is located in a SQLite database.



In the Jupyter Notebook you will find a detailed analysis of the data, including data cleaning and transformation, exploratory data analysis, and visualizations. We recommend that you start by reading the notebook.


The analysis yielded three concrete business recommendations, which we present below.


Visualizations


We selected three visualizations that correspond to our business recommendations. You can find them in the Visualizations folder.


Visualization 1
visualization1


This visualization shows the distribution of genres by ratings. We observe the highest earning genre is Drama, followed by Documentary,comedy,Horror, Drama/romance, thriller . But we also observe that some columns contain elements of another genre, but we were unable to create a function to separate the same.


Visualization 2
visualization2


This is a plot that shows the relationship between studio and average rating for movies.We observe that the highest rated studio is Focus studio, while the Highest earning studio was WB even the second rated Fox studios did not also garner good ratings. 


Visualization 3
visualization3


This visualization shows the earnings and expenses of the leading studios, where Warner Bros is the highest earning production studio, which can be attributed to the higher number of movies they release. We also observe that having a higher budget does not neccesarily mean that the earning will be the same as in the case between Fox and WB, where fox spent more that WB but this did not reflect on the sales.



Conclusion


In this project, we analyzed data from five different sources to generate insights for Microsoft's new movie studio. We presented three concrete business recommendations based on our analysis:


Microsoft should focus on producing Drama, Documentary, and comedy movies.
Microsoft should consider partnering with Warner Bros. and Focus studio for its new movie studio.
Microsoft should consider releasing movies during the holidays.
Microsoft can use these recommendations to help them decide what types of films to create.



Contact


If you have any questions or feedback, please feel free to contact us at https://www.linkedin.com/in/ian-macharia/.

