# E-CommerceProductReviewScrapper

This project is that of a product review web scraper that fetches reviews of a product from Flipkart, and stores the results in CSV file.

## Features

- Fetches reviews of a product from Flipkart
- Stores the results in CSV format

## Prerequisites

Before running the project, make sure you have the following installed:

- beautifulsoup4==4.9.1
- bs4==0.0.1
- Flask==1.1.2
- Flask-Cors==3.0.9
- urllib3==1.25.10

## Installation

1. Clone the repository:

git clone https://github.com/Vimiya/E-commerceProductReviewScrapper.git


2. Install the required dependencies:

pip install -r requirements.txt



## Usage

1. Run the Flask application:

python app.py

2. Access the application in your web browser at `http://localhost:8001`.

3. Enter the product name in the search field and submit the form.

4. The application will fetch reviews for the specified product and store the results in a CSV file.

## Folder Structure

The project has the following folder structure:

review-scraper/
├── app.py
├── templates/
│ ├── base.html
│ └── index.html
│ └── results.html
├── static/
│ ├── css/
    |--main.css
│ │ └── style.css
├── requirements.txt
├── runtime.txt
└── README.md


- `app.py`: The main Flask application file.
- `templates/`: Directory containing HTML templates.
- `templates/index.html`: Home page template with the search form.
- `templates/results.html`: Results page template displaying the reviews.
- `static/`: Directory containing static assets like CSS files.
- `static/css/style.css`: CSS file for styling the HTML templates.
- `static/css/main.css`: CSS file with size and font details for body, content of html page
- `requirements.txt`: installation requirements for this project.
- `runtime.txt`: Python version details for this project
- `README.md`: This file has details about what and how project is about.
