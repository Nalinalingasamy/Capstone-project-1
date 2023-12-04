# Capstone-project-1
YouTube Data Harvesting and Warehousing using SQL, MongoDB and Streamlit

##**YouTube Data Harvesting and Warhousing**

This project aims to harvest data from YouTube using Python scripting and store it in a NoSQL (MongoDB) database as a data lake. The harvested data can then be fetched from the NoSQL database and migrated to a SQL (MySQL) database for further analysis. Additionally, SQL queries can be executed on the MySQL database to answer specific questions related to the uploaded channel information.

##**Project Overview**

*The YouTube Data Harvesting and Warehousing project consists of the following components:*

**Streamlit Application:** Streamlit is a Python library that turns your code into interactive web apps.

**YouTube API Integration:** YouTube API integration lets you connect your app to YouTube's data like channels, videos, and comments, giving you superpowers to explore and analyze it. 

**MongoDB Data Lake:** MongoDB Data Lake is a central repository for storing all your data in its raw format, like a digital warehouse ready for big data analysis. Storage of the retrieved data in a MongoDB database, providing a flexible and scalable solution for storing unstructured and semi-structured data.

**SQL Data Warehouse:** Migration of data from the data lake to a SQL database, allowing for efficient querying and analysis using SQL queries.

**Data Visualization:** Presentation of retrieved data using Streamlit's data visualization features, enabling users to analyze the data through charts and graphs.

##**Skills Used**

*The following technologies are used in this project:*

*Python:* The programming language used for building the application and scripting tasks. 

*Streamlit:* A Python library used for creating interactive web applications and data visualizations.

*YouTube API:* Google API is used to retrieve channel and video data from YouTube.

*MongoDB:* A NoSQL database used as a data lake for storing retrieved YouTube data.

*SQL (MySQL):* A relational database used as a data warehouse for storing migrated YouTube data.

*Pandas:* A data manipulation library used for data processing and analysis.

*Plotly*: A data visualization library used for creating charts and graphs.

**Installation and Setup**

*To run the YouTube Data Harvesting and Warehousing project, follow these steps:*

#Install Python: Install the Python programming language on your machine.

#Install Required Libraries: Install the necessary Python libraries using pip or conda package manager. Required libraries include Streamlit, MongoDB , Pandas, SQL and Plotly.

#Set Up Google API: Set up a Google API project and obtain the necessary API credentials for accessing the YouTube API.

#Configure Database: Set up a MongoDB database and SQL database (MySQL) for storing the data.

#Configure Application: Update the configuration file or environment variables with the necessary API credentials and database connection details.

#Run the Application: Launch the Streamlit application using the command-line interface.

**Usage**

-->Once the project is setup and running, users can access the Streamlit application through a web browser. The application will provide a user interface where users can perform the following actions:

1.Enter YouTube channel ID to retrieve data for the channel.

2.Store the retrieved data in the MongoDB as a data lake.

3.Collect and store data for multiple YouTube channels.

4.Select a channel and migrate its data from the data lake to the SQL data warehouse.

5.Search and retrieve data from the SQL database.

6.Perform data analysis and visualization plotly.

**#Conclusion**

This project successfully built a data pipeline that harvested YouTube channel data, stored it as a flexible data lake in MongoDB, and transformed it into SQL for efficient querying. The resulting Streamlit app allows users to explore channel insights and discover hidden trends, showcasing the power of data-driven exploration. 


#**References**

Streamlit Documentation: https://docs.streamlit.io/

YouTube API Documentation: https://developers.google.com/youtube

MongoDB Documentation: https://docs.mongodb.com/

Python Documentation: https://docs.python.org/

SQL Documentation: https://dev.mysql.com/doc/
