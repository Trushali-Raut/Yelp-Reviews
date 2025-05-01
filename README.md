# Yelp-Reviews Analysis
Link to downlaod the dataset: https://business.yelp.com/data/resources/open-dataset/
Analyzed a large dataset of 5GB containing 7 million reviews across various businesses using SQL, Snowflake, and Python!

🔄 Workflow Overview:
📂 Data Ingestion → JSON files (Yelp reviews & business data)
☁️ Cloud Storage → Amazon S3 (AWS)
❄️ Data Warehousing → Snowflake (structured tables)
🤖 Sentiment Analysis → Python UDF
🔎 Business Insights → SQL queries

📌 Key Takeaways:
✅ Optimized large dataset handling by splitting a 5GB json file into multiple smaller datasets for efficient processing.
✅ Migrated the data from AWS S3 to Snowflake using the COPY command and optimized file formats.
✅ Created a UDF for sentiment analysis using Python.
✅ Wrote & executed 10+ complex analytical SQL queries to extract business insights, trends & sentiment patterns.
