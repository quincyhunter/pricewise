# Amazon Price Tracker

## Overview
Amazon Product Tracker is a Next.js application that allows users to enter Amazon product URLs to scrape and track product information, receiving updates when products are back in stock, at their lowest price, or go on sale.

## Features
- **Product Scraping**: Real-time scraping from Amazon using Bright Data's webunlocker.
- **Product Tracking**: Ability for users to track products and receive email updates.
- **Automated Updates**: Daily cron jobs to update product information and send notifications.
  
## Setup
1. Clone the repository:
git clone https://github.com/quincyhunter/Amazon-Price-Tracker
2. Install dependencies:
cd into the project directory and run npm install
3. Set up MongoDB and ensure it is running.
4. Set up your environment variables (see `.env.example` for a template).
5. Run the application:
npm run dev
## Usage
- **Enter Product URL**: Start by entering an Amazon product URL on the home page.
- **Track Product**: Choose to track the product to receive notifications.
- **Receive Updates**: Get email alerts on price drops and stock changes.
