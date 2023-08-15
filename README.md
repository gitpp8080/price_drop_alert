# price_drop_alert
Certainly! Here's a brief README for the provided code:

This Python script monitors the price of a product on online shopping websites (Amazon or Flipkart). 
It sends an email notification when the product's price drops below a specified threshold (in this case, 52000). 
The script uses web scraping and the `smtplib` library for email sending.

**Features:**

- Monitors the price of a product on Amazon or Flipkart.
- Sends an email alert when the product's price drops below some theshold value.
- Uses web scraping techniques to retrieve the current price from the provided URL.
- Supports Amazon and Flipkart websites by identifying the appropriate HTML elements for price extraction.
- Opens the product page in a web browser when the price drops.

**How to Use:**

1. Ensure you have the required libraries installed:
   - `requests`
   - `beautifulsoup4`
   - `smtplib`

2. Replace the following placeholders in the script with your actual information:
   - `URL`: The URL of the product page you want to monitor.
   - `sender_email`: Your Gmail email address.
   - `password`: Your Gmail app password (or your regular password if you have enabled less secure apps).
   - `receiver_email`: The recipient's email address.

3. Run the script using a Python interpreter.

4. The script will continuously monitor the product's price every 60 seconds.
5. If the price drops below threshold value, it will send an email notification and open the product page in a web browser.

