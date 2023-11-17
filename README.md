# YouTube Data Harvesting And Warehousing

YouTube-Data-Harvesting-and-Warehousing-using-SQL-MongoDB-and-Streamlit.

Problem Statement: The problem statement is to create a Streamlit application that allows users to access and analyze data from multiple YouTube channels.

NAME : Ramya Krishnan A

BATCH: D98

DOMAIN : DATA SCIENCE

DEMO VIDEO URL :  https://www.linkedin.com/posts/ramyakrishnan19_exciting-news-my-first-project-youtube-activity-7130814799369695232-Mv3O?utm_source=share&utm_medium=member_desktop

Linked in URL : www.linkedin.com/in/ramyakrishnan19

# Overview
This project is designed to extract data from YouTube using a provided channel ID, store the data in MongoDB Atlas, and provide options to migrate the data to a MySQL database for further analysis. The project utilises Python, various libraries, and Streamlit to create a user-friendly web page.

# Prerequisites
	•	Python 3.11 or higher
	
	•	VS Code
	 
	•	MySQL
	
	•	MongoDB Atlas
	
	•	YouTube API Key
	
  # Required Python libraries:
	
	•	pymongo
	
	•	googleapiclient
	
	•	mysql.connector
	
	•	streamlit
	
	•	plotly.express
	
	•	pandas
	
	•	re
	
	•	datetime

# Instructions

1. Install the required Python libraries:

	• pip install pymongo
	
	• pip install googleapiclient
	
	• pip install mysql-connector-python 
	
	• pip install streamlit
	
	• pip install plotly 
	
	• pip install pandas

2. Set up your MongoDB Atlas account and obtain the connection string.

3. Configure the MySQL server.

4. Copy the YouTube API key.

5. Create a .env file with the following information:

	• MONGODB_URI=your_mongodb_connection_string
	
	• MYSQL_HOST=your_mysql_host
	
	• MYSQL_USER=your_mysql_user
	
	• MYSQL_PASSWORD=your_mysql_password
	
	• MYSQL_DATABASE=your_mysql_database
	
	• YOUTUBE_API_KEY=your_youtube_api_key

6. Run the Streamlit web application

	• streamlit run app.py

# Features

•	Extracts and stores YouTube data in MongoDB Atlas.

•	Provides options to migrate data to a MySQL database.

•	Offers a Streamlit web page for easy interaction and visualization.
	
•	Allows users to view collected data in both MongoDB and MySQL formats.

•	Includes 10 predefined SQL queries for data analysis.

# Usage

• Go to YouTube, select the channel, go to "About," select "Share," and copy the Channel ID.

• Paste the Channel ID in the "Enter Channel ID" bar on the Streamlit web page.

• Click "Collect and Store Data" to store the data in MongoDB Atlas.

• After success, click "Migrate to SQL" to migrate MongoDB data to MySQL tables.

• Use the available options to view and analyze the collected data
