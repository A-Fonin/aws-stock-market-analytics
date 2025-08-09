# Stock Market Real-Time Data Analytics

## ☁️ Project Overview
#### This project builds a real-time stock market data analytics pipeline using AWS, leveraging event-driven architecture and serverless technologies.

![Architecture Diagram](https://imgur.com/dHXxUMX.png)


Key tasks include:

Streaming real-time stock data from yfinance using Amazon Kinesis Data Streams.
Processing data and detecting anomalies with AWS Lambda.
Storing processed stock data in Amazon DynamoDB for low-latency querying.
Storing raw stock data in Amazon S3 for long-term analytics.
Querying historical data using Amazon Athena.
Sending real-time stock trend alerts using AWS Lambda & Amazon SNS (Email/SMS).
