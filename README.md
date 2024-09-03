# Cleo-Analysis
This is the Jupyter Notebooks + Outputs used to analyse the data collected about the MSE user "Cleo"

## FUNCTIONS
get_OPdata(username, type): returns all questions and answers ('Q' and 'A') made by username

plot_timeline(questions, answers, start=None, end=None, figsize=(15, 10), title='Timeline'): plots question and answer dataframes between start and end dates

## Variables:
df_OPquestions: all questions asked by OP of posts Cleo responded to

df_OPanswers: all answers asked by OP of posts Cleo responded to 

df_OPall: all OPs of posts Cleo responded to 

df_CleoAnswers: Details about all of Cleo's answers (question and answer post date)

## Files:
CleoDataSetup: Using the SE API to import all the required data. 

CleoAnalysis: Analysing that data and plotting results

User Analysis ➞ UserCalendar: A program that plots the timeline for a given user id. 
