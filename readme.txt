Netflix Model

SEE PDF FOR SKETCH



TASK

The task was to model one of the following:

Netflix
Instagram
BBC News Website

"Think about what database tables this site would need, and what relationships they would have to each other. Are they one-to-one, one-to-many, or many-to-many?""



SOLUTION


Netflix Model


One to One

MOVIE
A table with a one to one relationship for a single Movie
containing id, name, description and length .

ACTORS
A table with a one to one relationship for a Single Actor
containing id, name and biography_id

DIRECTORS
A table with a one to one relationship for a Single Director
containing id, name and biography_id


One to Many

BIOGRAPHY
A table with a one to one many relationships for both director and actor (who could be both)
containing only id and bio_text

RATINGS
A table with one to many relationship for movie ratings.
containing id, rating and movie_id
to allow for different versions of a film (u, pg and 15, etc)

GENRES
A table with one to many relationship for genre,
containing id, genre, rating_id and movie_id
to allow for different genres to apply against a move (sci-fi and family, etc)


Many to Many

MOVIES
A table with Many to Many relationships for Movies
containing all the table reference_id(s)
to allow for more than one director, actor, rating and genre to be called against one another. A movie can have more than one director, actor, rating and genre, etc.
