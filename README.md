# YouTube_Channel_Statistics_Project

# Overview
This project demonstrates how to use the YouTube Data API to collect and analyze data from various YouTube channels. Create a YouTube API key, access different YouTube data using this API key, and write Python code to build this project.

Tool used: Jupyter Notebook

# Project Steps
## I. Create a YouTube API Key
To access YouTube data, you need to create a YouTube API key. This key serves as a credential to authenticate your requests. Follow the detailed steps below to create an API key:
1. Go to the Google Developers Console.
2. Create a new project or select an existing project.
3. Navigate to the Credentials section.
4. Click on Create Credentials and select API Key.
5. Copy the generated API key for use in this project.

## II. Set Up the Project Environment 
1. Create a Virtual Environment: conda create --name youtube_analysis python=3.8
2. Activate the Virtual Environment: conda activate youtube_analysis
3. Install Required Packages: conda install jupyter
    pip install google-api-python-client pandas seaborn

## III. Write Python Code
Part 1: Extract Channel Details
In this part, extract details from various YouTube channels, such as channel name, total number of subscribers, total views, and the total number of videos posted by each channel. Compare these details for multiple OTT Platform channels like Netflix, Hulu, Amazon Prime, SONU Liv and Apple TV.
1. Initialize YouTube API Client
2. Define Channel IDs
3. Get Channel Statistics

Part 2: Extract Video Details
In this part, extract details from a specific channel's videos, such as video title, total views and likes.

## IV. Data Analysis and Visualization
Load the collected data into a pandas DataFrame and analyze it. Create visualizations using Seaborn to compare different channels and video statistics.

# Conclusion
By following the above steps, you will be able to extract and analyze data from YouTube channels and videos using the YouTube Data API.
