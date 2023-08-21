# NoSQL Challenge - Database Setup and Exploratory Analysis

## Background

I embarked on a new challenge as a data professional, working with the UK Food Standards Agency's establishments data. The goal was to assist the editors of the food magazine, Eat Safe, Love, in evaluating food hygiene ratings. This project was divided into three parts: database setup, database update, and exploratory analysis.

## Part 1: Database and Jupyter Notebook Set Up

In this section, I used the `NoSQL_setup_starter.ipynb` notebook to perform the following tasks:

- Imported the data from the `establishments.json` file into a MongoDB database named `uk_food` with a collection named `establishments`.
- Confirmed the database and collection setup.
- Imported the necessary libraries, including PyMongo and Pretty Print (pprint).

## Part 2: Update the Database

I made modifications to the database as requested by the magazine editors. These changes included:

- Adding information about a new halal restaurant in Greenwich.
- Finding and updating the BusinessTypeID for "Restaurant/Cafe/Canteen."
- Removing establishments within the Dover Local Authority.
- Converting certain number values stored as strings to numeric types.

## Part 3: Exploratory Analysis

In this section, using the `NoSQL_analysis_starter.ipynb` notebook, I explored the database and answered specific questions posed by Eat Safe, Love:

1. Identified establishments with a hygiene score equal to 20.
2. Found establishments in London with a RatingValue greater than or equal to 4.
3. Determined the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant "Penang Flavours."
4. Calculated the number of establishments in each Local Authority area with a hygiene score of 0 and displayed the top ten local authority areas.

I used count_documents, pprint, and Pandas DataFrames to present the results clearly.

This project allowed me to work with real-world NoSQL data and perform data analysis to address specific business questions.
