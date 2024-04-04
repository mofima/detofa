# Web Scraping and Data Analysis Project

This project involves scraping product data from the `https://detofaentreprise.com` shopping website using Beautiful Soup and analyzing the collected data using pandas, seaborn, and matplotlib libraries in Python.

## Scraping Script

In the scraping jupyter notebook file (`scrapping.ipynb`), product data from various categories on the website is fetched and the HTML content for each category page is saved in a separate file in the folder named `firmin`.

## Analysis Script

In the analysis jupyter notebook file (`analysis.ipynb`), the saved HTML files are read and I parse the content using Beautiful Soup, extracts relevant information such as product name, category, and price, and creates a pandas DataFrame to store the data. It then performs various analyses on the collected data, including:

- Calculating the average price per category of products.
- Determining the most expensive and cheapest products.
- Examining the distribution of products across different categories.


## Results

The analysis reveals insights such as the average price per category, distribution of products across categories, and identifying the most expensive and cheapest products. Have a look at the `analysis.ipynb` file to see the visualizations I made from the analysis.

## Conclusion

This project demonstrates the process of web scraping using Beautiful Soup and analyzing the collected data to gain insights into product categories and pricing trends.

