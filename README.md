# capstone-project-1
Youtube Data Harvesting and Warehousing

YouTube Data Harvesting and Warehousing is a project that intends to provide users with the ability to access and analyse data from numerous YouTube channels. 

This project requires the following components:

Python:
Python is widely used in YouTube data harvesting and warehousing due to its versatility, extensive libraries, and ease of use. Python is the primary language employed in this project for the development of the complete application, including data retrieval, processing, analysis, and visualisation.

Google API Client :
The googleapiclient library in Python facilitates the communication with different Google APIs. Its primary purpose in this project is to interact with YouTube's Data API v3, allowing the retrieval of essential information like channel details, video specifics, and comments. By utilizing googleapiclient, developers can easily access and manipulate YouTube's extensive data resources through code.

Mongodb:
MongoDB is built on a scale-out architecture that has become popular with developers of all kinds for developing scalable applications with evolving data schemas.
MongoDB can be used in YouTube data harvesting and warehousing for storing and managing large volumes of unstructured or semi-structured data efficiently

PostgreSQL:
PostgreSQL is an open-source, advanced, and highly scalable database management system (DBMS) known for its reliability and extensive features. PostgreSQL can be used in YouTube data harvesting and warehousing for storing, managing, and analyzing structured and semi-structured data efficiently

YOUTUBE DATA SCRAPPING :
When engaging in the scraping of YouTube content, it is crucial to approach it ethically and responsibly. YouTube data scraping involves extracting information from YouTube, such as video metadata, comments, user profiles, and analytics, using web scraping techniques or the YouTube Data API. While scraping YouTube data can provide valuable insights and enable various applications, it raises several ethical considerations


Libraries:
1.googleapiclient.discovery

2.streamlit

3.psycopg2

4.pymongo

5.pandas

FEATURES:
The following functions are available in the YouTube Data Harvesting and Warehousing application:

Migration of data from the data lake to a SQL database for efficient querying and analysis.

Search and retrieval of data from the SQL database using different search options

Retrieval of channel and video data from YouTube using the YouTube API.

Storage of data in a MongoDB database as a data lak
