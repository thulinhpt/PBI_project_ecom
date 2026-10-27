# PBI_project_ecom
# Retail Analytics Pipeline

An end-to-end data project: raw e-commerce data → cleaned and modeled
warehouse → Power BI dashboard → Claude-powered insights.

## Business problem
[2-3 sentences: who would use this and what decisions it supports.
Example: "A retail team wants to understand which product categories
drive revenue and where late deliveries hurt repeat purchases."]

## Business questions
1. [Question 1]
2. [Question 2]
3. [Question 3]

## Architecture
[Diagram goes here later]

Raw CSV + FX API → Python ingestion → SQL Server (raw → staging → mart)
→ Power BI → Claude (review analysis / SQL assistant)

## Tech stack
- SQL Server (Docker)
- Python
- Power BI
- Claude API

## Data
Source: Olist Brazilian E-commerce dataset (Kaggle).
Download it separately and place the files in `data/`. Check the
dataset's license on its Kaggle page. The data is not included in this repo.

## How to run
1. Clone this repo
2. Copy `.env.example` to `.env` and fill in your values
3. [Docker and pipeline commands will go here]

## Project status
- [ ] Raw ingestion
- [ ] Staging and cleaning
- [ ] Star schema
- [ ] Data quality tests
- [ ] Power BI dashboard
- [ ] Claude features
- [ ] Documentation and demo video

## Author
[Your name] | [LinkedIn link]