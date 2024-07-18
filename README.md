# Automated-Web-Scraping
Price monitoring of Crypto-Bitcoin using Web Scraping in Python

# Bitcoin Price Tracker

## Table of Contents
 - [Introduction](#introduction)
 - [Project Description](#project-description)
 - [Prerequisites](#prerequisites)
 - [Getting Started](#getting-started)
 - [How It Works](#how-it-works)
 - [Usage](#usage)
 - [Contributing](#contributing)

## Introduction
This Python project demonstrates how to scrape product information from a website and track the price changes of the crypto product. In this case, we are tracking the price of a crypto currency-Bitcoin on the coinmarketcap.com website

## Project Description
- We use Python and the BeautifulSoup library for web scraping.
- The scraped data (Bitcoin and change of price) is automatically stored in a CSV file every hour

## Prerequisites
Before running the project, ensure you have the following dependencies installed:
- Python 3.x
- BeautifulSoup (bs4)
- Requests
- Pandas

## Getting Started
1. Clone this repository to your local machine.
2. Install the required Python packages.

## How It Works
- The script scrapes the product title and price from the coinmarketcap website using web scraping techniques.
- It stores this information in a CSV file for tracking.
- automated_crypto_pull() function runs every hour and automatically stores the Bitcoin price with the timestamp

## Usage
1. Update the URL variable in the script to your desired product's URL.
2. Run the script.

## Contributing
If you want to contribute to this project or suggest improvements, please create an issue or a pull request.
