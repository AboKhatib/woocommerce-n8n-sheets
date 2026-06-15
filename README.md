WooCommerce to Google Sheets Automation via n8n

This project syncs WooCommerce store orders with Google Sheets automatically. It transfers data instantly when customers place orders.

Features

Webhooks capture data in real time.
An IF node filters orders to pass processing status only.
A JavaScript snippet merges multiple item names into a single cell separated by commas.
The workflow updates existing rows or adds new ones using the Order ID to prevent duplicates.

Project Files

workflow.json holds the complete n8n workflow.
README text provides the setup documentation.

Setup Instructions

Download the workflow.json file to your computer.
Open n8n and select import from file to load the workflow.
Configure the Google Sheets node with your account credentials.
Enter your specific spreadsheet ID and sheet name.
Copy the production webhook URL from the first node.
Paste this URL into your WooCommerce webhook settings for order creation.
