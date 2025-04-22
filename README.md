##Name: Krishna Sri G
##eDx username: krishnasri_
##GitHub username: Krishnaasrii
##City: Hyderabad
##Country: India
##video Demo:https://youtu.be/2615-oDj-Ew?si=2o8QMz-Zp0-VwwqW
##Date of video Recording: 27-04-2025
##Description:
MOVIE RECOMMENDATION SYSTEM
A Python-based movie recommender that allows users to search for movies, filter by genre, and get random movie suggestions using the MovieLens dataset.

load_movies(file_path="ml-32m/movies.csv") – Loads movie data from a CSV file into a list of dictionaries.

search_movies(movies, query) – Searches for movies with titles containing a given keyword.

filter_by_genre(movies, genre) – Filters the movie list to include only movies of a specified genre.

get_random_movie(movies) – Returns a random movie from the list.

recommend_similar_movies(movie, movies) – Recommends up to 5 movies that share genres with a selected movie.

main() – Runs the main program loop, handling user input and displaying search, filter, and recommendation results.

MovieLens for providing the dataset.

### Files:
- **project.py**: Main Python program for movie searching and recommendations.
- **test_project.py**: Contains tests for the functions in `project.py`.
- **requirements.txt**: Lists required Python libraries (e.g., pytest).
- **ml-32m/**: Directory containing the MovieLens 32M dataset.

### Installation:
1. Clone or download the project files.
2. Install the dependencies by running:
    ```bash
    pip install -r requirements.txt
    ```
