# Twitter-scrapping-with-python-and-present-it-interactive-web-application

This project is about scraping Twitter data using the snscrape library, filtering tweets based on hashtags and date range, and downloading the filtered data as CSV or JSON files. We will use the Streamlit library to create a user-friendly interface for this project. We will also integrate the MongoDB database to upload and store the scraped data.

## Step 3: Importing Libraries

- snscrape to scrape Twitter data
- pandas for data manipulation
- streamlit for creating a user interface
- datetime to work with dates
- PIL to work with images
- numpy to work with arrays
- json to work with JSON data
- pymongo for working with MongoDB

## Step 2: Scrape Twitter Data

- Create an empty list to store the scraped tweets.
- Use snscrape.TwitterSearchScraper to scrape tweets based on a query string.
- Append tweet information to the tweet list.
- Convert the tweet list into a pandas DataFrame.
- Save the DataFrame to a CSV file.

## Step 3: Create Streamlit Interface

- Set the page configuration with a title and layout.
- Add a header and image to the interface.
- Read the CSV file via pandas and add a button to display the loaded dataset and its length.
- Create functions to convert DataFrame to CSV, JSON, and dictionary.
- Add download buttons to download the dataset as CSV and JSON files.
- Add a filter section to filter the data based on given hashtag.
- Define a function to filter the data based on a given hashtag.
- Add download buttons to download the filtered data as CSV and JSON files.
- Add date range filter to filter the data based on the date range.
- Define a function to filter the data based on a given date range.
- Create MongoDB connection to upload the dataset. 
- Add a button to upload the dataset to MongoDB.
- Add a success message when the dataset is uploaded to MongoDB.

## Step 4: Run the Application
- Run the Streamlit application on your local machine.
- Use the interface to view, filter, and download Twitter data.
