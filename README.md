# lightcast_skills_python_to_csv

# Skills Data Script
This repository contains a Python script to fetch and process skills data from the Lightcast API. The script retrieves the latest skills version metadata, extracts available fields, and gathers all skills data, converting it into a structured DataFrame. The data is then cleaned and flattened to ensure usability for further analysis.

# Features
- Fetches OAuth token for secure API access.
- Retrieves and processes the latest skills version metadata.
- Extracts all available skills data with detailed field information.
- Cleans and flattens nested JSON structures for easy data manipulation.
- Outputs the processed data as a CSV file for further analysis.

# Use Cases
1. Workforce Planning: Predict future workforce requirements based on skill trends and align talent acquisition strategies with market needs.
2. Skills Gap Analysis: Identify skill shortages within the organization and develop targeted training and development programs.
3. Recruitment: Enhance job descriptions with current market data and attract candidates with the most in-demand skills.
4. Employee Development: Create personalized development plans and promote continuous learning and upskilling.

# Requirements
1. Python 3.x
2. Requests
3. Pandas

# Set Up Environment Variables
- Replace the CLIENT_ID and CLIENT_SECRET ("XxXxX") in skills_data.py with your actual Lightcast API credentials. You can obtain these credentials by signing up on the Lightcast API page, https://lightcast.io/products/data/API-form

# Steps to Access Data
1. Register for an API client ID and secret on the Lightcast platform.
2. Authenticate using the credentials sent to the registered user's email.
3. Use the credentials in your coding language of choice to access the data.
