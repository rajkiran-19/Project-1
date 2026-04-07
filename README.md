# Project-1
Sample POC

Project 1: Your Sample Use Case (To Build)
Use Case: "E-Commerce Product Performance Tracker"
You need to analyze which product categories are generating the most revenue based on daily sales files.
Your Task: Design and Build
I have provided the "problem" and the "data sources." You must now design the architecture and code the pipeline. 
The Data Sources:
• Sales Data (CSV): Contains order_id, product_id, amount, and order_date.
• Product Metadata (JSON): Contains product_id, category, and brand.
Requirements for Your Pipeline:
1. Architecture: Draw (or list) how data moves from these two files into a final "Reporting Table."
2. Join Strategy: You must join the CSV and JSON data so you can see revenue by category.
3. Data Quality: Add a check to remove any rows where amount is negative or null.
4. End Goal: A BigQuery table that shows Category, Total_Revenue, and Total_Orders. 
dbt Labs +1
How to Start Without Installing Anything:
1. Create a free account on Google Cloud Console.
2. Open Google Colab and connect it to your GCP project using from google.colab import auth; auth.authenticate_user().
3. Upload your sample CSV/JSON files to a GitHub Gist or Google Drive to act as your "Source."
4. Write the Python code in Colab to read these files, clean them with the Pandas library, and push them to BigQuery. 
<img width="1075" height="901" alt="image" src="https://github.com/user-attachments/assets/cad33ef9-0868-411a-b0f1-e9684f625ae4" />
