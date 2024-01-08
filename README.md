# YouTube-Data-Harvesting-and-Warehousing-using-SQL-MongoDB-and-Streamlit
Skills take away from this project: Python scripting, Data Collection, MongoDB, Streamlit, API integration, Data Management using MongoDB and SQL

Streamlit- is an open-source Python library that allows you to create web applications for data science and machine learning projects with minimal effort. It simplifies the process of turning data scripts into shareable web applications by providing a high-level interface.

Python- is a versatile and high-level programming language known for its readability, simplicity, and extensive community support.

A Google API Client- refers to the tools and libraries provided by Google to facilitate the integration of applications with various Google services and APIs.
Purpose:
Google API Clients are designed to simplify the process of interacting with Google services, such as Google Maps, YouTube, Google Drive, and others, by providing developers with pre-built libraries and tools.
Its primary purpose in this project is to interact with YouTube's Data API v3, allowing the retrieval of essential information like channel details, video specifics, and comments.

MongoDB- is built on a scale-out architecture that has become popular with developers of all kinds for developing scalable applications with evolving data schemas. As a document database, MongoDB makes it easy for developers to store structured or unstructured data. It uses a JSON-like format to store documents.

POSTGRESQL: PostgreSQL is an open-source, advanced, and highly scalable database management system (DBMS) known for its reliability and extensive features. It provides a platform for storing and managing structured data, offering support for various data types and advanced SQL capabilities.

YouTube data scraping- involves extracting information from YouTube's publicly accessible content, such as video details, channel information, comments, and more. While web scraping itself is a common practice, its ethical implications depend on the intent, methods used, and adherence to terms of service.
It can be ethical when conducted with transparency, respect for privacy, adherence to terms of service, and a clear understanding of the legal and ethical implications. Developers and researchers should prioritize responsible data practices to ensure a positive impact on the platform and its users.

REQUIRED LIBRARIES:

1.googleapiclient.discovery
2.streamlit
3.psycopg2
4.pymongo
5.pandas

FEATURES: The following functions are available in the YouTube Data Harvesting and Warehousing application: Retrieval of channel and video data from YouTube using the YouTube API.
Storage of data in a MongoDB database as a data lake.
Migration of data from the data lake to a SQL database for efficient querying and analysis.
Search and retrieval of data from the SQL database using different search options.
