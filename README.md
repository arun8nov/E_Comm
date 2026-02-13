# E-Commerce Data Lakehouse

This project is a data lakehouse for an e-commerce company. It is built using DataBricks 

## Architecture

The data lakehouse follows a medallion architecture with three layers:

- **Bronze Layer**: Raw data ingested from source systems (e.g., transactional databases).
- **Silver Layer**: Cleaned, conformed, and integrated data.
- **Gold Layer**: Business-level aggregates and dimensional models optimized for analytics.

## Getting Started

### Prerequisites

- **DataBricks Account**: Access to a DataBricks environment.
- **dbt**: Installed and configured for DataBricks.
- **Python**: Version 3.8 or higher.

