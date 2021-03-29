# The-Github-History-of-the-Scala-Language

## Project Description
Open source projects contain entire development histories, such as who made changes, the changes themselves, and code reviews. In this project, you'll be challenged to read in, clean up, and visualize the real-world project repository of Scala that spans data from a version control system (Git) as well as a project hosting site (GitHub). With almost 30,000 commits and a history spanning over ten years, Scala is a mature language. You will find out who has had the most influence on its development and who are the experts.

The dataset includes the project history of Scala retrieved from Git and GitHub as a set of CSV files.

## Topics
- Importing and Cleaning Data
- Data manipulation
- Data visualization

## Dependencies
- `pandas`
- `matplotlib`

## The Structure of this Notebook is as Follows:
1. Load, join and clean data.
2. Visualize the evolution of the number of contributions of Scala.
  - Calculate the number of pull requests submitted each month during the project's lifetime.
  - Create a bar plot to see the trend.
3. Investigate if there's a high barrier of entry by looking at the distribution of the number of pull requests submitted by each user.
  - Plot a histogram.
  - There are a large number of people that only contribute a small number of pull requests, indicating that the project is welcoming of new contributor.
4. Identify developers who made the most pull requests to a given file.
5. Plot the number of pull requests two specific developers submitted.
  - `counts_wide = counts.pivot_table(index='date', columns='user', values='pid', fill_value=0)`
  - There contribution in a given file is also plotted.
   
