# Dataset Description: Tiki Product Data Collection

## Overview
This dataset includes product information collected from Tiki.vn (a Vietnamese e-commerce platform).  
It focuses on product metadata, pricing, ratings, and review details to support market and consumer behavior analysis.

## Data Source
- Platform: Tiki.vn
- Collection Method: Web scraping using Python (requests, BeautifulSoup) or Tiki’s public API.
- Type of Data: Public product information.
- Collection Date: (You can fill the date when you ran the script)

## Data Fields
- `product_id`: Unique identifier for each product.
- `product_name`: Name of the product.
- `price`: Current listed price (in VND).
- `original_price`: Original price before discount.
- `discount_rate`: Percentage of discount.
- `rating_average`: Average rating from customer reviews.
- `review_count`: Number of reviews.
- `category`: Product category (e.g., Electronics, Home Appliances, Books).
- `seller_name`: Name of the seller or store.
- `brand`: Brand name (if available).
- `url`: Direct link to the product page.

## Purpose
The dataset can be used for:
- Price comparison analysis across sellers.
- Demand forecasting based on rating and review trends.
- Identifying top-performing brands.
- Market sentiment analysis for product categories.

## Ethical Note
All data are publicly available from Tiki.vn and are collected solely for educational and research purposes.  
No personal user data were accessed or stored.
