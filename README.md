# Pirati
Testing
Hello!
I must say that this is not my day to day job, so I had to spend more time on resarch.It took me half an hour for two SQL task, and another 3 hours for this python scripts.Also this is my first submision over github, so I am not sure I have done it properly. :)

Task one - The way I see solution to this task is that we need to have 2 csv files. One for today and one saved from yesterday so we can compare number of clicks or views and calculate today values. Also when saving file, I would add timestamp to filename so it could be used again if neccessary. I did not include that into my code. First script use 2 csv files named Report1 and Report2 (stored on C:/Report/) and makes dictionary out of them. In second script we substract values of dictionaries if they are there or if not that column does not apear, or we can write 0 value or same value from day before so that we get 0 value for today.Also we can use average value for this filed.New dictionary is saved in same order always for easier use on next day.Problem is all data that can't be used before use of these scripts because we can't get date out of them.

Task two - I have imported csv file inito sql server and wrote queries that return tables as requested in docuent.(2a and 2b)
Task three - Using same querry from task two I have created new table with columns Expense area and Expence type. ( querry 3a ), and for final transformation into requested table i used function pivot, but data I have got from this querry has several values, mostly are null values.
