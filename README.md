# Books Web Scraping and Analysis

This repository contains a Python-based project that demonstrates web scraping and data analysis. The project involves extracting book-related data from the [Books to Scrape](https://books.toscrape.com/) website, followed by exploratory data analysis (EDA) and visualizations to gain insights from the collected data.

## Project Structure

The repository includes the following Jupyter Notebooks:

1. **`books-website-scraping.ipynb`**  
   - Extracts book data such as titles, ratings, prices, and availability from the website.
   - Saves the scraped data into a CSV file for further analysis.

2. **`books-data-analysis.ipynb`**  
   - Loads the scraped data from the CSV file.
   - Cleans and preprocesses the dataset (e.g., converting ratings to numerical values).
   - Performs EDA and visualizations to analyze pricing, ratings, and other trends.

## Features

- **Web Scraping**:
  - Extract book details including:
    - Book ID (UPC)
    - Title
    - Category
    - Rating
    - Price
    - Stock availability (Stock status)
    - Quantity available

- **Exploratory Data Analysis (EDA)**:
  - Visualizes key metrics such as price distributions and rating trends.
  - Identifies relationships between features like price and rating.

## Tools and Libraries

- **Web Scraping**:
  - `requests`
  - `BeautifulSoup`

- **Data Manipulation**:
  - `pandas`

- **Data Visualization**:
  - `matplotlib`
  - `seaborn`
  - `squarify`
 

## About the Dataset
The scraped dataset is available on Kaggle: [Books Data on Kaggle](https://www.kaggle.com/datasets/randsj/books-dataset/data)

### Dataset Columns:

1. **ID**: Unique Product Code (UPC) for each book.
2. **Title**: The title of the book.
3. **Category**: Genre or category of the book.
4. **Price [£]**: Price in GBP (£).
5. **Rating**: Star rating (One to Five) based on customer reviews.
6. **Availability**: Whether the book is in stock.
7. **Quantity**: The number of available copies.
