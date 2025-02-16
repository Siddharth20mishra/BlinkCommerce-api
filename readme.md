## Overview
The *Grocery Scanner API* is a powerful tool designed to scrape product data from multiple online grocery stores, including *Blinkit, Zepto, and Instamart*. It ensures comprehensive data collection, enabling users to retrieve up-to-date product details efficiently.

## Features
- *Multi-Store Support*: Extracts product details from Blinkit, Zepto, and Instamart.
- *Efficient Data Extraction*: Utilizes optimized algorithms to handle diverse website structures and dynamic content.
- *Scalability*: Designed to handle multiple requests while maintaining performance.
- *RESTful API*: Easy-to-use endpoints for fetching grocery product data.

## Technologies Used
- *Python*
- *FastAPI* (for building the API)
- *BeautifulSoup & Selenium* (for web scraping)
- *Vercel* (for deployment)

## Installation
To run the API locally, follow these steps:

sh
# Clone the repository
git clone https://github.com/Siddharth20mishra/BlinkCommerce-api
cd grocery-scanner-api

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt

# Run the API
uvicorn main:app --reload


## Usage
Once the API is running, you can access the documentation at:
- *Swagger UI*: [https://grocery-scanner-api.vercel.app/docs](https://grocery-scanner-api.vercel.app/docs)

Example request using curl:
sh
curl -X GET "https://grocery-scanner-api.vercel.app/products?store=blinkit&query=milk" -H "accept: application/json"



## License
This project is licensed under the *MIT License*.

## Links
- *GitHub Repository*: [Grocery Scanner API](https://github.com/Siddharth20mishra/BlinkCommerce-api)
