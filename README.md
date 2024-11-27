# Automatic Music Review ETL Pipeline using AWS
Code for an end-to-end pipeline in AWS that extracts and processes reviews from pitchfork.com using Beautiful Soup, Lambda and CloudWatch, stores it in a DynamoDB table, then sends an email update using SES.

I developed this project since I love listening to music and I want an automatic way to discover new albums. I also wanted to learn cloud computing using AWS, so I decided to develop a pipeline that detects new reviews from pitchfork.com, extracts relevant information from the reviews, adds them to a database, then sends me an email update.

## Pipeline Architecture Diagram
![Pitchfork Scraper](https://github.com/user-attachments/assets/6c862b76-85fd-4513-bdec-f5259d6439f1)


## Sample Email
<img width="982" alt="image" src="https://github.com/user-attachments/assets/7ad7b8cf-6ef3-4341-bd3c-23f9918f3c50">
