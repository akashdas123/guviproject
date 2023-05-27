# guviproject
This project aims to develop a user-friendly Streamlit application that utilizes the Google API to extract information on a YouTube channel, stores it in a MongoDB database, migrates it to a SQL data warehouse, and enables users to search for channel details and join tables to view data in the Streamlit app.

library used 
googleapiclient.discovery# [Youtube API libraries]
json
pymongo
mysql.connector
sqlalchemy
pymysql
pandas
streamlit 

From each video, viewCount, likeCount, video ID, comments with commentators name, no of comments, video title, and thumbnails are extracted.
then its passed to mongodb and sql database and then specific queries are applied to extract the data in form of table 

coded in pycharm
mongodb atlas 
mysql

