# NoSQL Challenge Summary

The UK Food Standards Agency assesses various establishments nationwide, assigning them food hygiene ratings. You've been engaged by the editors of "Eat Safe, Love," a food magazine, to analyze portions of this rating data. This analysis aims to aid their journalists and food critics in selecting future article topics.

## Objectives
1. Familiarize yourself with NoSQL databases, specifically MongoDB.
2. Utilize the PyMongo library to interact with MongoDB databases using Python.
3. Learn how to construct aggregation pipelines for data retrieval.

## Part 1: Database Setup and Jupyter Notebook Initialization (NoSQL_setup_starter.ipynb)
1. Imported the provided data from the "establishments.json" file into a database named "uk_food" and a collection named "establishments" using the Terminal command:
   `mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json`
2. Created an instance of the MongoDB client.
3. Updated the database with new entries.
4. Modified field data types to facilitate queries.

## Part 2: Exploratory Analysis (NoSQL_analysis_starter.ipynb)
The editors at Eat Safe, Love have specific questions they want addressed to guide their location choices.
1. Initialized a MongoDB client instance.
2. Conducted analysis using queries and generated result dataframes.
3. Converted rating values to integers and handled string-to-null and null-to-null conversions for analysis purposes.
4. Performed analysis employing aggregation and pipelines.
