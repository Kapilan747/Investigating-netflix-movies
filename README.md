Project Title: Netflix Movie Duration Analysis (1990s)
Description
This project analyzes the duration of movies released in the 1990s and available on Netflix. The analysis includes visualizations, calculations of the mode, and filtering of short movies (less than 90 minutes). The project provides insights into the distribution of movie lengths and explores trends within a specific genre—Action movies.

Dataset
Source: Netflix movie data (1990s)
Columns: Includes fields such as movie title, duration, genre, and more.
The dataset contains multiple columns including the year of release, genre, and duration of the movie.

Tools and Libraries Used
Python 3.12.4
Jupyter Notebook
Pandas
Matplotlib
Seaborn
Data visualization and analysis libraries

Installation
Clone the repository:
'''bash
git clone https://github.com/Kapilan747/netflix-duration-analysis.git

Navigate to the project directory:
'''bash
cd netflix-duration-analysis

Install required packages:
'''bash
pip install -r requirements.txt

Run the Jupyter Notebook:
'''bash
jupyter notebook notebook.ipynb

Analysis Overview
The analysis in this project involves:

Data Cleaning: Removing unnecessary columns and handling missing values.
Data Visualization: Plotting histograms to visualize the distribution of movie durations.
Statistical Insights: Calculating mode and filtering movies under 90 minutes.
Action Movie Focus: Additional focus on Action genre movies and counting how many are shorter than 90 minutes.
Results
The mode of movie durations in the dataset is 94 minutes.
The majority of Action movies from the 1990s on Netflix are shorter than 90 minutes.


