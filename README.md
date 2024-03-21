# Earthquake to Twitter

## Description
This repository contains a Python script that retrieves real-time earthquake data from the USGS Earthquake Catalog API and automatically posts updates to Twitter. Stay informed about recent earthquakes worldwide with real-time alerts directly on Twitter.

## Features
- Retrieves recent earthquake data from the USGS Earthquake Catalog API.
- Parses earthquake data to extract information about each earthquake (magnitude, location, depth, time).
- Composes a tweet with earthquake details and posts it to Twitter using the Twitter API.
- Allows for customization of Twitter API credentials and tweet formatting.

## Dependencies
- Python 3.x
- Tweepy library (`pip install tweepy`)
- Requests library (`pip install requests`)

## Usage
1. Clone the repository to your local machine.
2. Install dependencies by running `pip install -r requirements.txt`.
3. Replace `'YOUR_TWITTER_API_KEY'`, `'YOUR_TWITTER_API_SECRET'`, `'YOUR_TWITTER_ACCESS_TOKEN'`, and `'YOUR_TWITTER_ACCESS_TOKEN_SECRET'` in the script with your actual Twitter API credentials.
4. Run the script using `python earthquake_to_twitter.py`.

## Configuration
- Replace placeholders in the script with your Twitter API credentials obtained from the Twitter Developer Portal.
- Adjust the API endpoint URL in the script if needed (e.g., for fetching earthquake data from a different source).
- Customize tweet formatting and content as desired.

## Contributing
Contributions to improve the script or add new features are welcome! Please fork the repository, make your changes, and submit a pull request for review.


