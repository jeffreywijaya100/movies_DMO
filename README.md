# movies_DMO
The following exercises are based on the movies.tsv and movie-ratings.tsv files in movies directory. The column delimiter in these files is a tab, so make sure to use that splitting each line. 

Each line in the movies.tsv file represents an actor played in a movie. If a movie has ten actors played in it, there are rows for that movie.

1.	Compute the number of movies each actor was in. The output should have two columns: actor, count. The output should be ordered by the count in descending order
2.	Compute the highest-rated movie per year and include all the actors played in that movie. The output should have only one movie per year, and it should contain four columns: year, movie title, rating, a semicolon-separated list of actor names. This question requires a join between movies.tsv and movie-ratings.tsv files. There are two approaches to this problem. The first is to figure out the highest-rated movies per year and then join with a list of actors. The second one is to perform the join first and then figure out the highest-rated movies per year and a list of actors. The result of each approach is different from the other one. Why do you think that is?
3.	Determine which pair of actors worked together most. Working together is defined as appearing in the same movie. The output should have three columns: actor1, actor2, and count. The output should be sorted by the count in descending order. The solution to this question requires doing self-join.
