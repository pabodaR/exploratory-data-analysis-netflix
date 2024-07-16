### Exploratory Data Analysis with Netflix Dataset

## Table of Contents
1. [Introduction](#introduction)
2. [Project Overview](#project-overview)
3. [Dataset](#dataset)
4. [Data Preprocessing](#data-preprocessing)
5. [Analysis](#analysis)
6. [Results](#results)

## Introduction
This project involves conducting an exploratory data analysis (EDA) on a Netflix dataset to uncover insights into the types of content available, their distribution, and trends over time. The analysis aims to understand content types, production countries, prominent directors and actors, genres, and the evolution of content length.

## Project Overview
- **Objective:** Gain insights into Netflix content and trends.
- **Features:** Data exploration, preprocessing, visualization, and statistical analysis.

## Dataset
- **Source:** [Netflix Dataset on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows/data)
- **Description:** The dataset includes information about Netflix titles such as type (movie or TV show), title, director, cast, country, date added, release year, rating, duration, and listed in genres.

## Data Preprocessing
- Handling missing values
- Handling duplicate values: Removed duplicate entries to maintain data integrity.
- Encoding categorical variables: Converted categorical data (e.g., genres, country) into numerical format for analysis.
- Normalization/Standardization: Applied normalization to duration data for uniformity.
- Feature engineering: Extracted relevant features.

## Analysis
1. **Content Type Distribution:**
   - **Objective:** Analyze the distribution of different types of content (movies vs. TV shows).
   - **Analysis:** 
     - Counted the number of movies and TV shows.
     - Analyzed the distribution of content types over the years.

2. **Top Countries by Content Production:**
   - **Objective:** Identify which countries produce the most content.
   - **Analysis:** 
     - Identified the top 10 countries by the number of titles produced.
     - Visualized the leading content-producing countries.

3. **Director and Cast Analysis:**
   - **Objective:** Understand the most prolific directors and frequent collaborators.
   - **Analysis:** 
     - Identified the top directors by the number of titles directed.
     - Analyzed the top actors with the most appearances in Netflix titles.

4. **Genre of Content:**
   - **Objective:** Analyze genres of content.
   - **Analysis:** 
     - Counted the amount of content by genre.
     - Visualized the popularity and diversity of genres.

5. **Content Length Evolution:**
   - **Objective:** Investigate how the average length of movies has changed over time.
   - **Analysis:** 
     - Calculated the average movie duration by release year.
     - Visualized the evolution of movie lengths to identify trends.

## Results
- **Content Type Distribution:** 
  - The dataset contains a higher number of movies compared to TV shows.
  - The distribution over the years shows a steady increase in both movies and TV shows, with a significant rise in recent years.

- **Top Countries by Content Production:**
  - The USA leads in content production, followed by India and the UK.
  - Visualizations highlight the dominance of certain countries in content creation.

- **Director and Cast Analysis:**
  - A small number of directors and actors are highly prolific, contributing to a large number of titles.
  - Top directors and actors are identified, providing insights into frequent collaborators.

- **Genre of Content:**
  - Drama, Comedy, and International movies are the most common genres.
  - The genre analysis shows a wide range of content available on Netflix, catering to diverse audiences.

- **Content Length Evolution:**
  - The average length of movies has shown a slight increase over the years.
  - Visualizations illustrate the trends in movie durations, providing insights into changing viewer preferences.

