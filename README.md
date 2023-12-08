# netflix-dashboard-using-tableau    
## Goal:  
* Find the most popular genres.
* Most Popular Rating Category.
* Filter the show based on their type and name.
* Create a dashboard that filters the show and extracts all the show's information, like its genre, description, release year, rating, and the date when it was uploaded on Netflix.
## Data Description:  
The data contains the following 11 columns:  
* **show_id**: It contains the unique id of the show.
* **type**: The type includes whether it is a TV show or a movie.
* **title**: It is the tile of the show.
* **director:** The name of the director of the show.
* **cast:**  The cast of the show.
* **country:** The country that released the show. 
* **date_added:** When it was added to Netflix.
* **release_year**: The releasing year of the show.
* **rating**:  The rating of the show.
* **duration**: the duration of the shows, movies in minutes, and TV shows in the number of seasons.
* **listed_in**: The category of the show; it could be documentary, Crime TV, Dramas, Comedy, etc.
* **description**: The short description of the show.

## Data Visualization:  

### Dashboard:  


The interactive dashboard below shows the important data insights from the Netflix dataset. The dashboard shows the count of movies and TV shows, the percentage difference between movies and TV shows, the top 10 genres, and the number of TV shows and movies by year. The data can be filtered by type and movie name.
![Dashboard](https://github.com/muhammadfhaider12/netflix-dashboard-using-tableau/blob/main/netflix-insights/Dashboard.png)     

### Analysis and Conclusion:  


The figure below shows the movies per year from 2010 to 2029. However, most of the shows are from 2019, which counts 1424 movies and 592 TV shows. 

![Show Count per Year](https://github.com/muhammadfhaider12/netflix-dashboard-using-tableau/blob/main/netflix-insights/Distinct%20Show%20Count.png)  

There are 8807 shows in the data. However, the figure shows that the data contains more movies as compared to TV shows. The data from movies accounts for nearly 70% (6131) of the dataset, while TV shows account for 30% (2676).  

![TV Shows VS Movies](https://github.com/muhammadfhaider12/netflix-dashboard-using-tableau/blob/main/netflix-insights/Movie%20VS%20Show%20Counts.png)  

Following are the top 10 genres, with 'Dramas, International Movies' and documentaries being the first and second most popular genres, respectively. However, 'Dramas, International Movies, and Romantic Movies' is the least popular genre.  

![Top 10 Genres](https://github.com/muhammadfhaider12/netflix-dashboard-using-tableau/blob/main/netflix-insights/Top%2010%20Genres.png)  

The figure below indicates the ratings of the shows.TV-MA has significantly high ratings, while NC-17, TV-Y7-FV, and UR have the least ratings.  

![Rating Count](https://github.com/muhammadfhaider12/netflix-dashboard-using-tableau/blob/main/netflix-insights/Rating%20Counts.png)  
