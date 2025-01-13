# IMDB Movies Data Analysis Project

## Overview
This project performs comprehensive analysis of movie data from IMDB using MySQL. It explores various aspects of the film industry including movies, ratings, actors, directors, and production companies to derive meaningful insights for business decisions.

## Database Schema
The project uses the IMDB database with the following key tables:
- `movie`: Contains movie details (title, year, duration, etc.)
- `genre`: Movie genres
- `director_mapping`: Maps directors to movies
- `role_mapping`: Maps actors/actresses to movies
- `names`: Contains actor and director information
- `ratings`: Movie ratings and votes

## Features

### 1. Movie Analysis
- Total number of movies by year and month
- Movies by country (focus on USA and India)
- Genre distribution and analysis
- Movie duration analysis by genre
- Multilingual movies analysis
- Box office performance analysis

### 2. Rating Analysis
- Movies by average and median ratings
- Hit movies analysis (rating > 8)
- Genre performance based on ratings
- Rating-based movie classification
    - Superhit: Rating > 8
    - Hit: Rating between 7-8
    - One-time-watch: Rating between 5-7
    - Flop: Rating < 5

### 3. Production Analysis
- Top production houses by votes
- Hit movie production analysis
- Multilingual movie production
- Global production company analysis

### 4. Actor/Director Analysis
- Top actors by movie count and ratings
- Top actresses in Hindi movies
- Director performance analysis
- Actor/Actress ranking by country

## Advanced Analysis Features
1. Running totals and moving averages of movie durations
2. Weighted average calculations for actor/actress ratings
3. Complex ranking systems using window functions
4. Multilingual movie analysis
5. Time-based analysis using date functions

### Running Analyses
Each analysis section is organized as numbered queries (Q1-Q29). To run an analysis:
1. Select the desired query
2. Execute in your MySQL client
3. Results will be formatted according to the specified output format

## Key Insights From Analysis
1. Drama is the most produced genre
2. Movies with higher ratings tend to have higher vote counts
3. Production companies focusing on quality over quantity show better average ratings
4. Multilingual movies show significant market presence
5. Actor/Director combinations show patterns in successful movies

## Contributing
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License
This project is available under the MIT License.


