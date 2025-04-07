# AWS Clickstream Data Pipeline

A production-ready data engineering solution for real-time clickstream analytics using AWS cloud services. This project demonstrates end-to-end data pipeline architecture, from data ingestion to analytics dashboards.

## Project Overview
This data engineering project implements a scalable, real-time data pipeline to capture, process, and analyze clickstream data from a global cafe chain's website. The solution enables data-driven business decisions through automated data collection and analytics.

## Business Problem Solved
- Lack of Customer Insights: Provided clear visibility into customer behavior
- Inefficient Marketing: Enabled data-driven marketing decisions
- Operational Inefficiencies: Streamlined operations through real-time insights
- Expansion Uncertainty: Delivered actionable data for location decisions

## Generative AI as Co-pilot
I leveraged Generative AI as a co-pilot to create a clear, concise dashboard in AWS. The dashboard provided fresh insights, enabling our business client to implement scalable revenue-boosting improvements while reducing security risks and minimizing data noise.

### Real-time Analytics Dashboard
![AWS CloudWatch Dashboard showing key business metrics](https://cdn.prod.website-files.com/678689ad79214b873fce7420/67f3ed87f5a7743671651c25_Building%20a%20Data%20Pipeline%20for%20Business%20Insights.webp)

Key insights from the dashboard:
- Cities visiting the menu the most (pie chart)
- Cities placing the most orders (tabular data)
- Regions placing the most orders (donut chart)
- Regions visiting the website the most (bar chart)

## Architecture
The solution uses several AWS services in an integrated pipeline:
- Amazon EC2: Hosts the web server
- Amazon CloudWatch: Handles logging, monitoring, and dashboarding
- Amazon S3 & S3 Select: Manages data storage and querying
- AWS Cloud9: Provides development and management environment
- IAM: Controls secure access and permissions

## Project Demonstrations
### Clickstream Log Analysis
[![Why Observing Logs is Important for Clickstream](https://cdn.loom.com/sessions/thumbnails/c3f97477b4c047d4bbd84508ef67748b-with-play.gif)](https://www.loom.com/share/c3f97477b4c047d4bbd84508ef67748b?sid=8c1ab6f1-9b2e-4b6b-bf99-c27afcf5ae31)

### Dashboard Implementation
[![Dashboard Walkthrough](https://cdn.loom.com/sessions/thumbnails/5ed5400678794b16a1df379aec51ede0-with-play.gif)](https://www.loom.com/share/5ed5400678794b16a1df379aec51ede0?sid=809b9b94-46b0-484a-b7ca-48e600af168f)

## Implementation Details & Architecture
[Your implementation pictures will be added here]

## Implementation Details
- Designed and implemented scalable data collection pipeline
- Created real-time monitoring dashboards
- Implemented secure data storage and access patterns
- Enabled efficient data querying using S3 Select

## Documentation
- [Setup Guide](docs/setup-guide.md)
- [Monitoring Guide](docs/monitoring-guide.md)
- [Cost Analysis](docs/cost-analysis.md)

## Business Impact
- Enhanced understanding of customer behavior
- Improved marketing effectiveness
- Optimized cafe operations
- Data-driven expansion decisions

## Repository Structure
```
aws-cafe-analytics/
├── architecture/
│   └── diagrams/
├── docs/
│   ├── setup-guide.md
│   ├── monitoring-guide.md
│   └── cost-analysis.md
├── src/
│   ├── cloudwatch/
│   ├── iam/
│   └── scripts/
└── examples/
    └── sample-queries/
