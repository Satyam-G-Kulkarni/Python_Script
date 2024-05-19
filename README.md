# Python_Script

# Overview
This repository contains a Python script designed to fetch and organize citation data from an API. The script retrieves paginated data, processes it to group citations by their corresponding responses, and displays the results in a structured format.

# Features
Fetches data from a specified API endpoint with pagination support.

Extracts and groups citation data based on responses.

Handles exceptions and errors gracefully.

Outputs grouped citation data in a readable format.


# Requirements

Python 3.6 or higher
requests library

# Installation

Clone the repository.

Install the required Python packages

# Usage

Open the script file and locate the main function.

Ensure the api_url variable is set to the desired API endpoint:

Run the script.

The script will output the grouped citation data in the console.

# Code Description

# Functions

fetch_all_data(api_url)

Fetches all pages of data from the given API URL.

Handles pagination and collects data into a list.

Returns the complete list of data.

group_citations_by_response(data):

Groups citations by their associated response.

Iterates through the data to extract source IDs and links.

Returns a dictionary with responses as keys and lists of citations as values.

# fetch_and_group_citations(api_url):

Combines the functions fetch_all_data and group_citations_by_response.

Returns the grouped citations.

# Main Function

The main function serves as the entry point of the script. It:

# Defines the API URL.

Fetches and groups the citation data.

Prints the grouped citations in a formatted manner.

# Error Handling

The script includes basic error handling for:

HTTP errors (non-200 status codes).

Exceptions during the request or data processing.

# Contributing

Feel free to open issues or submit pull requests with improvements or bug fixes. Contributions are welcome!
