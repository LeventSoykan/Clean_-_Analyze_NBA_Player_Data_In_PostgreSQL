Clean and Analyze NBA Player Data in PostgreSQL
===============================================

This project aims to clean and analyze NBA player data using PostgreSQL. The raw data is obtained from a CSV file containing information on NBA players such as player name, height, weight, points per game, rebounds per game, etc.

The steps involved in the project are as follows:

1.  **Data Cleaning:** The raw data is cleaned using Python and the Pandas library. The data is inspected for any missing values, duplicates, and inconsistencies. The cleaned data is then stored in a new CSV file.
    
2.  **Database Creation:** A new database is created in PostgreSQL and the cleaned data is loaded into the database. The database schema is designed to reflect the structure of the data.
    
3.  **Data Analysis:** SQL queries are used to analyze the data in the database. The queries are designed to answer specific questions such as the players with the highest points per game, the players with the highest rebounds per game, and the average height of players in the league.
    

Technologies Used
-----------------

*   Python
*   Pandas
*   PostgreSQL
*   SQL

How to Use
----------

To run this project, follow these steps:

1.  Clone the repository to your local machine.
2.  Install the necessary dependencies using `pip install -r requirements.txt`.
3.  Run the Jupyter notebook `Clean_and_Analyze_NBA_Data.ipynb` to clean the data and create the database.
4.  Use any SQL client to connect to the PostgreSQL database and run queries to analyze the data.

Future Improvements
-------------------

This project can be improved in the following ways:

*   Adding more data to the database to provide a more comprehensive analysis.
*   Creating a web application to display the analysis results.
*   Automating the data cleaning and database creation process.

Resources
---------

*   [NBA Player Data](https://www.kaggle.com/drgilermo/nba-players-stats)
*   [PostgreSQL Documentation](https://www.postgresql.org/docs/)
*   [Pandas Documentation](https://pandas.pydata.org/docs/)
*   [SQL Documentation](https://www.w3schools.com/sql/default.asp)

