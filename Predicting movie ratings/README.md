# Movie Ratings Database

This repository contains a database for tracking movies watched, including their titles, directors, genres, and ratings.

## Database Schema

The database schema includes the following table:

### movies_watched

| Column        | Data Type | Description             |
|---------------|-----------|-------------------------|
| id            | INTEGER   | Unique identifier       |
| title         | TEXT      | Title of the movie      |
| director      | TEXT      | Director of the movie   |
| genre         | TEXT      | Genre of the movie      |
| year_watched  | INTEGER   | Year the movie was realeased |
| my_rating     | INTEGER   | my rating for the movie |
| imdb_rating   | INTEGER   | IMDb rating for the movie   |

