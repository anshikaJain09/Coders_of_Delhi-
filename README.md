# Coders_of_Delhi-
People Recommendation System

📌 Project Overview
This project demonstrates how data preprocessing, cleaning, and algorithm design can be combined to build a recommendation system in Python. The system suggests two types of recommendations:
People You May Know → Based on mutual connections.
People You Might Like → Based on preference patterns.
It also includes data preprocessing and data cleaning steps to ensure high-quality inputs before building the recommendation logic.

⚙️ Tech Stack
Python (Core implementation)
Pandas & NumPy (Data handling)
JSON (Raw dataset format)
Jupyter Notebook (Development & experimentation)

📂 Project Structure
├── 01_data_preprocessing.ipynb   # Preprocessing raw JSON data (formatting, structuring)
├── 02_data_cleaning.ipynb        # Cleaning missing/inconsistent data
├── 03_people_you_may_know.ipynb  # Recommender for mutual connections
├── pages_you_might_like.ipynb    # Recommender for preference-based suggestions

🔑 Key Highlights

1.Data Preprocessing
Converted raw JSON data into structured format.
Extracted relevant attributes and standardized them.

2.Data Cleaning
Handled missing values, duplicates, and inconsistencies.
Ensured datasets are ready for building robust recommendation logic.

3.People You May Know (PYMK)
Suggests new connections using mutual friend counts.
Implements dictionary-based logic and ranking system.

4.People You Might Like (PYML)
Suggests people with similar interests or preferences.
Creates personalized recommendations by analyzing user data patterns.

🚀 How It Works

Load and preprocess the dataset (01_data_preprocessing).
Clean and validate the dataset (02_data_cleaning).
Generate “People You May Know” suggestions (03_people_you_may_know).
Generate “People You Might Like” suggestions (pages_you_might_like).

📊 Results

A working recommendation engine similar to those used in social networks.
Demonstrates data preprocessing, cleaning, and algorithm design skills.
Highlights practical application of Python in recommendation systems.

✨ Future Enhancements

Implement graph-based algorithms (e.g., NetworkX for social graph analysis).
Add collaborative filtering for advanced recommendations.
Integrate with a Power BI dashboard to visualize user connections.
