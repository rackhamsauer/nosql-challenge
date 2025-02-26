# nosql-challenge
Penang Flavours Analysis
This repository contains the work completed for the Penang Flavours analysis, which involved setting up a MongoDB database, inserting dataset records, and performing analysis using Jupyter Notebooks. The project primarily focused on database operations and data analysis, with an attempt to convert latitude and longitude data for further analysis.

Overview
The project consisted of multiple steps, including:

Setting up MongoDB:
Ensuring MongoDB was properly loaded and configured on my local machine.

Loading the Dataset:
Loading the Penang Flavours dataset into MongoDB and confirming that the data was correctly pulled and structured.

Data Insertion:
Inserting information into the MongoDB database via terminal, specifically for the Penang Flavours dataset.

Analysis in Jupyter Notebook:
Analyzing the dataset using Jupyter Notebook and ensuring accuracy by cross-checking my work with MongoDB shell commands.

While I made progress, there was one key issue with converting latitude and longitude from strings to decimals, which impacted the completion of my analysis.

Data Handling
MongoDB Shell Operations:
I used the MongoDB shell to load data and perform operations like updateMany, set, and attempting to parse latitude and longitude from strings into floats. Despite my attempts using geocode.latitude to extract and convert the data, I was unable to successfully transform the coordinates into the required format.

Code for Latitude and Longitude Conversion:
While I wasn't able to complete the latitude and longitude conversion, I have included the code that would have been used in the MongoDB shell to show the intended approach. This code would have helped in converting the latitude and longitude fields from strings to decimals.

Challenges Faced
Latitude and Longitude Conversion:
The main challenge in this project was converting the latitude and longitude values from strings to decimals. Despite attempts using various MongoDB functions and data parsing methods (including updateMany, set, and parsing with float), I was unable to achieve the desired result.

I tried using geocode.latitude to reference the parent and sub-class structure to extract and convert the data, but was not successful.

As a result, the portion of my analysis that relied on the geographic data is incomplete.

Tools and Resources Used
MongoDB for database operations and data storage.
Jupyter Notebook for data analysis and manipulation.
MongoDB Shell for testing queries and checking the integrity of the database.
ChatGPT, Stack Overflow, Peers, and Tutor for troubleshooting and guidance throughout the process.
How to Use
Clone the repository to your local machine.
Ensure you have MongoDB and Python installed, along with necessary libraries like pymongo for interacting with the database.
Follow the steps to load the dataset into MongoDB as outlined in the provided code.
Open the Jupyter Notebook to explore the analysis and check the attempts at transforming the latitude and longitude values.
Conclusion
While the assignment was not fully completed due to issues with converting geographic data, I was able to load and work with the dataset using MongoDB and Jupyter Notebook. I have included the code that I would have used to fix the conversion issue, and I hope this serves as a helpful reference for anyone working on a similar task.
