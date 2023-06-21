# What_makes_movie_a_hit
This project focuses on analyzing the factors that contribute to the success of a movie, particularly in terms of net profit and revenue. By examining various variables such as popularity, genre, budget, and release year, we aim to gain insights into what makes a movie financially successful. The project utilizes a dataset obtained from the TBDb API website through Kaggle, which contains information about movies, including their titles, genres, cast, release dates, popularity scores, runtimes, budgets, and revenues.

Data Cleaning

The dataset obtained from Kaggle required cleaning before analysis. Several non-numeric columns contained NA values and zeros, such as cast, crew, release status, and overview. To ensure accuracy and improve the analysis, the following cleaning steps were performed:
Unnecessary rows were dropped using the subset function.
Dates were converted from strings to numeric format using the numeric function.
NA values and zeros were removed from the dataset.
The resulting clean dataset was used for regression and other analyses.

Data Visualization

Data visualization plays a crucial role in uncovering insights from the dataset. Several visualizations were created to provide a better understanding of the movie industry:
Quarterly Movie Releases: The number of movies released each quarter was plotted to observe any patterns or trends. It was observed that the highest number of releases occurred in the last two quarters, possibly due to the holiday season. Surprisingly, the number of releases in the first two quarters was not significantly lower.
Top 10 Highest Grossing Movies: A table was generated to display the top 10 movies with the highest net profit. It was found that popularity alone was not the sole determinant of a movie's revenue and profit. Avatar, with a popularity score of around 42, had the highest return on investment (ROI). On the other hand, Harry Potter and the Deathly Hallows Part 2 had the highest popularity among the top 10 movies, with a considerable ROI.
Highest Grossing Genres: A visualization of the highest grossing genres was created, revealing that adventure, action, comedy, and drama had the highest net profit. It was observed that adventure and action genres had higher average popularity scores.

Hypothesis Testing

To test the hypothesis that higher popularity leads to higher net profit for movies, the popularity scores were divided into two sets: movies with popularity less than 20 and movies with popularity more than 20. A histogram revealed that the majority of movies fell within the 0 to 20 popularity range.
