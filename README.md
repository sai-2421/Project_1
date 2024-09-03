# Project_1 - YouTube Data Harvesting and Warehousing using SQL and Streamlit

This project gathers data from YouTube channels using the YouTube Data API, followed by meticulous processing and subsequent warehousing.

Problem Statement

To create a Streamlit application that allows users to input a YouTube channel ID and retrieve channel details using the YouTube Data API. The gathered information will be stored in a SQL data warehouse. The application should offer various search options for accessing and querying the data from the SQL database.

Overview

By leveraging the Google YouTube API, the application can retrieve detailed information about YouTube channels and videos, store it in a SQL database, and enable users to perform complex searches and analyses on the data. The application is user-friendly and provides a seamless way to interact with and visualize YouTube channel data.

Take Away Skills

The following skills were acquired from the project: Youtube API integration, Python scripting, Data Management using MySQL, Streamlit app development, Pandas, Plotly data visualization.

Work Flow

1.API Integration:

Establish a connection to the YouTube API to fetch detailed information about channels, videos, and comments. The Python Google API client library is utilized to submit requests and retrieve the necessary data.

2.Data Collection:

The Streamlit app provides a user-friendly interface where users can input a YouTube channel ID. The app then retrieves and displays the relevant channel information.

3.Data Storage:

Collected data is systematically stored in a structured MySQL database. This organized storage ensures that the data is optimized for efficient querying and analysis within the MySQL environment

4.Data Analysis:

Using SQL join operations, the application processes user queries to extract meaningful insights from the stored data, helping to identify trends and performance metrics across channels.

5.Data Visualization:

The app leverages Streamlit's capabilities to present the analyzed data through interactive tables and charts, enabling users to easily interpret and explore the insights derived from the YouTube channels.

Usage of App

After the project has been successfully set up and activated, users can interact with the Streamlit application through a web browser. Through the application's user-friendly interface, users can carry out the following tasks:

Input a YouTube channel ID to fetch data for the specified channel.

Gather information and keep it in a SQL data warehouse for numerous YouTube channels.

Check out the uploaded channels' details.

Utilise a variety of search tools to locate and retrieve data from a SQL database.

Use these integrated features to perform analysis and visualisation of channel data.


Method of use

Follow these steps,to use this project :

1 Set up the streamlit package : pip install streamlit

2.Run the Streamlit app: streamlit run app.py

3.The web browser will launch instantly, allowing you to access it.

4.Open your web browser if it doesn't start automatically. By starting a new tab and typing the following URL, you can visit it:http://localhost:8501

5.Click the store data button after entering the channel ID in the text field on the Extract tab.

6.The database will hold the channel's details.

7.In the views tab,Select the questions that best fit your needs.

Conclusion

This project aims to develop a user-friendly Streamlit application that leverages the Google API to extract detailed data from YouTube channels. Once collected, the data is stored in a SQL data warehouse. The Streamlit app enhances the data exploration process by enabling users to efficiently search for channel information and perform table joins.

References

YouTube Data API [https://developers.google.com/youtube/v3/getting-started]

Streamlit App [https://docs.streamlit.io/library/api-reference]

MySQL [https://pypi.org/project/pymysql/]

Pandas [https://pandas.pydata.org/docs/]

Plotly [https://plotly.com/python-api-reference/]
