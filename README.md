# Instacart-Analysis
*A bootcamp project that required using Python and Jupyter to first clean, organize, and merge multiple large data sets. After data was combined and organized, I then used Python to visualize certain aspects of this data.*

# Project Description

## A quick comment in praise of the design of this course
For this project, I was given a few very large (to me) datasets, and had to use Python to clean and analyze them. Something I found particularly great about this project is the amount of *learning by doing* that was required. Answers and methods to find them were not always given, so there was a lot of Googling that had to be done to find solutions for myself. I came out of it with a good understanding of a few fundamental techniques for handling data in Python, but also a huge respect for the amount of knowledge there is for me to gain if I continue to practice with it. 

In short, this project made me fall in love with Python.


## Some Key Skills Gained
The files in this repository contain Jupyter files of all of the work I had to do for this project, but I would like to give a quick summary of some of the skills I gained while working on this project:
- Troubleshooting Python and Jupyter when the programs themselves are not cooperating
- Understanding how to read the Python language, making searching for answers and finding my own errors much easier
- Merging large data sets based on specific keys
- Creating category flags to further filter data to gain insight
- Using loc() instead of loops to make filtering more efficient
- Using crosstabs to quickly find possible interesting relationships between variables
- Importing data and saving as dataframes, exporting dataframes into various file formats
- Creating basic statistical summaries of variables
- Visualizing data in Python 


## Basic Walkthrough of the Worlflow of this Project
1. Clean two large data sets, 'orders' and 'products'. 
2. Wrangle this new, larger data set to only include relevant information. Rename weird columns, drop useless ones, etc.
3. Merge this data set with a third data 'customers' data set based on the customer id within each order. Exclude sensitive information that could comprimise a customer's identity.
4. Create new flags for customers based on a few of their ordering habits, product preferences, family status, and where they are located in the US.
5. Run some statistical analysis on these groups
6. Visualize the analysis
7. Complete a fictional report in Excel for instacart revealing the findings.
