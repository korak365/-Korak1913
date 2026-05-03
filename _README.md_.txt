# Amazon Hidden Coupons Scraper

🔍 **Finds discounts not visible on main search pages**

An Apify Actor that scrapes Amazon search results and product pages to discover hidden coupons and discounts that aren't immediately visible to regular users.

## Features

✅ Scrapes Amazon product pages for hidden coupon information  
✅ Extracts coupon codes and discount percentages  
✅ Fast HTML parsing with Cheerio (10x faster than browsers)  
✅ Configurable crawl depth and request limits  
✅ Structured JSON output with product details  
✅ Runs locally or on Apify cloud platform  

## Requirements

- Node.js >=20.0.0
- npm or yarn
- Apify CLI (for deployment)

## Installation

```bash
# 1. Clone or download this project
git clone <repository-url>
cd amazon-hidden-coupons-scraper

# 2. Install dependencies
npm install