# Movie-Recommendation
The provided code defines a CineMatch class to manage a movie collection. This class offers methods to add movies, search for movies by title or genre, recommend the top N movies based on ratings, and delete movies by title. Here’s a concise summary of the functionality:

Initialization (__init__ method):

Initializes an empty list self.movies to store movie data.
Add Movie (add_movie method):

Adds a movie with specified title, genre, and rating to the collection.
Prints a confirmation message.
Search by Title (search_by_title method):

Searches for movies containing the given title (case-insensitive) and prints matching results or a message if no matches are found.
Search by Genre (search_by_genre method):

Searches for movies containing the given genre (case-insensitive) and prints matching results or a message if no matches are found.
Recommend Top N Movies (recommend_top_n method):

Recommends and prints the top N movies based on their ratings, sorted in descending order.
Delete Movie (delete_movie method):

Deletes a movie by its title (case-insensitive) and prints a confirmation message or a message if the movie is not found.
