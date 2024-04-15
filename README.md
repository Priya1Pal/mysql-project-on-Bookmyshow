# mysql-project-on-Bookmyshow

Creating a MySQL project for a BookMyShow-like application involves designing a database to manage information related to movies, theaters, bookings, users, and other relevant entities.
This project aims to develop a simplified version of an online movie ticket booking system inspired by BookMyShow. 
The system allows users to browse movies, view showtimes, book tickets, and manage bookings seamlessly. It leverages MySQL for database management.

## Database Schema

The database schema includes tables for users, movies, theaters, showtimes, bookings, and possibly additional entities depending on the project's requirements.

- Users: Stores user information including username, email, and password.
- Movies: Contains details about available movies such as title, genre, and release date.
- Theaters: Stores information about theaters including name and location.
- Showtimes: Represents specific showtimes for movies in theaters, including start time and end time.
- Bookings: Tracks bookings made by users, including the number of tickets, total amount, and booking time.

## 30 SQL Questions

Below are 30 SQL questions related to the BookMyShow project, covering various aspects of the system's functionality and database operations:

Consider the `movies` table for generating 10 questions: -

Question 1: Retrieve the titles of all movies in the database.
Question 2: Find the genres of movies released on or after a specific date.
Question 3: Identify the number of movies in each genre.
Question 4: List the movies released before a certain year.
Question 5: Find the most recent movie in the database.
Question 6: Count the total number of movies in the database.
Question 7: Display the titles and release dates of movies.
Question 8: Retrieve the titles of movies that belong to a specific genre.
Question 9: Identify the oldest movie in the database.
Question 10: List the titles of movies along with their respective genres.

These questions cover various aspects of querying the `movies` table, such as selecting specific 
columns, filtering based on conditions, and aggregating data.


Consider the relationship between the `movies` and `showtimes` tables for generating
10 questions: -

Question 1: Retrieve the titles and genres of all movies that have showtimes.
Question 2: Find the theaters where a specific movie is currently being shown.
Question 3: Identify the number of showtimes for each movie.
Question 4: List the movies playing in a particular theater.
Question 5: Find the start times of all showtimes for a specific movie.
Question 6: What are the showtimes for the movie " The Matrix" at the theater named " Cinema 
Paradise"
Question 7: What is the username of the user who made the booking with ID is 2
Question 8: Identify the theaters with the most showtimes.
Question 9: List the movies along with the corresponding theater locations
Question 10: Find the total number of tickets booked for each movie.

These questions involve queries that require joining the `movies` and `showtimes` tables to 
gather information from both tables.


Consider a relationship between the `movies`, `showtimes`, and `bookings` tables for 
generating 10 questions:

Question 1: Retrieve the titles and genres of all movies for which bookings have been made.
Question 2: Find the usernames and email addresses of users who booked tickets for a specific 
 movie.
Question 3: Identify the total number of tickets booked for each movie.
Question 4: List the movies, showtimes, and corresponding theater names for a specific date.
Question 5: Find the total number of tickets booked by a specific user.
Question 6: Display the movie titles, showtimes, and booking details for a specific user.
Question 7: Retrieve the total revenue generated by each movie.
Question 8: Find the users who booked tickets for a movie in a specific genre.
Question 9: List the movies, showtimes, and booking details for a specific theater.
Question 10: Identify the most popular showtime (maximum bookings) for each movie.

These questions involve querying information from all three tables by performing joins and 
aggregations
