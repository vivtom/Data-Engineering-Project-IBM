# Data-Engineering-Project-IBM

Project Description: Data Engineering Project IBM
Overview
The Data Engineering Project IBM is designed to provide hands-on experience with various aspects of data engineering, using the Skills Network Cloud IDE based on the open-source project Theia. The project covers data extraction, transformation, and loading (ETL) processes, as well as web scraping and database management.

Objectives
Familiarize with Integrated Development Environment (IDE):

Utilize the Skills Network Cloud IDE for project development.
Data Extraction, Transformation, and Loading (ETL):

File Types: Practice extracting data from CSV, JSON, and XML file formats.
Data Transformation: Convert the extracted data into the required format.
Database Loading: Save the transformed data in a ready-to-load format for an RDBMS.
Detailed Tasks
Data Extraction:

Import Libraries:
glob: For file type access.
pandas: For reading CSV and JSON files.
xml.etree.ElementTree: For parsing XML files.
datetime: For logging.
Functions:
extract_from_csv(file_to_process): Reads data from CSV files.
extract_from_json(file_to_process): Reads data from JSON files.
extract_from_xml(file_to_process): Reads data from XML files.
extract(): Combines data from all file types into a single DataFrame.

Data Transformation:
Transform Function:
Convert heights from inches to meters and weights from pounds to kilograms, rounding off to two decimal places.

Data Loading:
Load Function:
Save the transformed data to a CSV file.
Implement logging to track the progress of the ETL process.

Web Scraping:
Libraries:
requests: To fetch web page contents.
BeautifulSoup: To parse HTML.
pandas: For data storage and manipulation.
sqlite3: For database operations.
Task: Extract information about the top 50 movies with the best average rating.
Save the extracted data to a CSV file and a database table.

Database Management:
Create Database: Use SQLite to create a database and manage data.
Load Data: Load data from CSV files into database tables.
Querying: Perform basic SQL queries to retrieve information from the database.

