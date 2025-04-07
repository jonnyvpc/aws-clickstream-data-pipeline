# AWS Clickstream Data Pipeline

A production-ready data engineering solution for real-time clickstream analytics using AWS cloud services. This project demonstrates end-to-end data pipeline architecture, from data ingestion to analytics dashboards.

## Project Overview
This data engineering project implements a scalable, real-time data pipeline to capture, process, and analyze clickstream data from a global cafe chain's website. The solution enables data-driven business decisions through automated data collection and analytics.

## Business Problem Solved
- Lack of Customer Insights: Provided clear visibility into customer behavior
- Inefficient Marketing: Enabled data-driven marketing decisions
- Operational Inefficiencies: Streamlined operations through real-time insights
- Expansion Uncertainty: Delivered actionable data for location decisions

## Architecture
The solution uses several AWS services in an integrated pipeline:
- Amazon EC2: Hosts the web server
- Amazon CloudWatch: Handles logging, monitoring, and dashboarding
- Amazon S3 & S3 Select: Manages data storage and querying
- AWS Cloud9: Provides development and management environment
- IAM: Controls secure access and permissions

## Project Demonstrations
- [Why Observing Logs is Important for Clickstream](https://www.loom.com/share/c3f97477b4c047d4bbd84508ef67748b)
- [Dashboard Walkthrough](https://www.loom.com/share/5ed5400678794b16a1df379aec51ede0)

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
