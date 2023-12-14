# Jeopardy! Data Analysis and Difficulty Exploration
This project explores the world of Jeopardy! questions and answers using Python and Pandas. We analyze a dataset of questions and answers, filter them based on keywords, calculate difficulty metrics, and even explore the diversity of answers.

## Project Goals:

- Investigate Jeopardy! data: Load and analyze a dataset of Jeopardy! questions and answers.
- Filter by keywords: Develop a function to filter questions based on a list of keywords.
- Calculate difficulty: Define and compute the "difficulty" of questions based on their value.
- Analyze answer diversity: Explore the variety of answers and identify the most common ones.
### Key functionalities:

- Data Loading and Cleaning:
  - Load data from jeopardy.csv into a DataFrame.
  - Address data cleaning challenges, including column names (consider renaming them).
- Keyword Filtering:
  - Implement a function to filter questions based on a list of keywords.
  - Ensure the function handles case-sensitivity and substring matches.
  - Test and refine the function for robustness.
- Difficulty Calculation:
  - Convert `Value` column from string to float.
  - Define a metric for question difficulty based on value (e.g., average value).
  - Calculate difficulty for filtered questions based on specific keywords.

### Answer Analysis:
- Develop a function to count the number of unique answers for a filtered dataset.
- Identify the most frequent answers for specific topics.

### Technologies used:
- Python
- Pandas
  
### Project Output:

A Jupyter notebook named `This is Jeopardy.ipynb` containing the implemented code and analysis.
This `README.md` file documenting the project goals, functionalities, and outcomes.
