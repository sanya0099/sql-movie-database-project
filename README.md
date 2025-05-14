# 🎬 Behind the Screens: A SQL-Based Movie Streaming Platform

This project presents the design and implementation of a **relational database system** for a movie streaming platform. The system is developed using SQL to represent real-world components such as **users, movies, genres, watch history, ratings, and subscription plans**. It demonstrates how structured data management supports key features of a streaming service like tracking user behavior, organizing content, and enabling data-driven recommendations.

---

## 📌 Project Objectives

- Model a scalable relational database for a movie streaming platform.
- Ensure **data normalization**, **integrity**, and **efficient querying**.
- Enable key platform functionalities like:
  - User registration and subscriptions
  - Genre-based movie categorization
  - Watch history tracking
  - Rating and review analysis
  - Subscription and revenue monitoring

---

## 🗃️ Database Schema Overview

The project uses an **Entity-Relationship (ER) diagram** and 6 core tables:

| Table          | Description                                                                 |
|----------------|-----------------------------------------------------------------------------|
| `Users`        | Stores user details (ID, name, email, signup date)                         |
| `Movies`       | Contains movie data (ID, title, release year, genre ID)                    |
| `Genres`       | Lists genres (e.g., Action, Comedy, Drama)                                 |
| `WatchHistory` | Logs user-movie interactions with timestamps                               |
| `Ratings`      | Collects user ratings on a scale of 1 to 5                                 |
| `Subscription` | Tracks user subscription plans, durations, and payment statuses            |

---

## 🔍 Sample Data

Example entries are included for each table. For instance:

- Users like **Alice Smith** and **Bob Johnson** with corresponding watch and rating histories.
- Movies such as **Edge of Tomorrow**, **The Godfather**, and **Interstellar**.
- Genre classification for easier filtering and analytics.

---

## 🔄 SQL Functionality

### 🧠 Subqueries
- Users who watched more than the average number of movies.
- Movies with average rating above 4.5.
- Most popular genres based on content volume.

### 🔗 Joins
- Combine users with their watch histories and movie details.
- Calculate average ratings per movie, joined with genre data.
- Identify users with active subscription plans.

### 👁️ Views
- `TopRatedMovies`: Movies with rating > 4.
- `UserActivitySummary`: Number of movies watched per user

