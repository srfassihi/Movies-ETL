# Movies-ETL

## Summary
Created a pipeline to automate the task of reading in three separate data sources by refactoring the existing code as a function using the following steps:
1. Read the three data files
2. Clean the wiki file
3. Clean the Kaggle file and merge with wiki
4. Process and merge the Ratings file
5. Push the final dataframe to a database table

## Note to TA / Grader:

I ran into multiple issues with this module stemming from the difficulty of creating a large function. I had difficulties debugging my code in Deliverable 3 and struggled to find the issue with the BCS Assistants but finally discovered the issue. I had issues with my PostgreSQL password information as well as my PythonData environment not recognizing my SQLAlchemy plugin. I tried using online resources but the steps are very hard to do on Mac and didnt make sense. Resetting passwords are very tricky in PostgreSQL. I was able to finish the code but not able to push the data to my table. 
