# Ivan Salazar

**Data and Analytics Engineer | SQL | Python | Data Quality | BI**

I build data pipelines and reporting systems that turn noisy API and event data
into reliable analytical models. My work emphasizes data quality, root-cause
analysis, understandable reporting, and automation that makes recurring work
easier to operate.

## Technical focus

- **Languages:** Python and SQL
- **Warehouses and databases:** Snowflake, BigQuery, PostgreSQL
- **Orchestration and processing:** Dagster, Airflow, PySpark, Pandas
- **Cloud and storage:** AWS, Amazon S3, Google Cloud
- **Analytics:** Tableau, Looker Studio, dimensional modeling, data validation
- **AI-assisted workflows:** LLM evaluations, automated issue detection, and
  reviewed AI-assisted development

## Featured projects

### [Grocery Price Pipeline](https://github.com/ivanrsalazar/grocery-price-pipeline)

A Dagster-orchestrated BigQuery pipeline that collects daily Kroger API price
snapshots for a canonical grocery basket across U.S. store locations.

- Organizes data into bronze, silver, and planned gold layers
- Preserves raw source payloads for auditability
- Normalizes products with version-controlled matching rules
- Uses LLM-assisted evaluations to identify false-positive product matches
- Separates ingestion, validation, and analytical modeling concerns

### [Crypto Kline Data Pipeline](https://github.com/ivanrsalazar/kline-pipeline)

A real-time OHLCV pipeline for Binance US and Kraken market data.

- Combines WebSocket ingestion with REST backfills for missing intervals
- Uses hourly S3 partitions and Dagster orchestration
- Models PostgreSQL data through bronze, silver, and gold layers
- Produces idempotent one-minute facts and larger analytical intervals
- Adds completeness checks, Slack alerts, and Looker Studio monitoring

### [NFT Sales Data Pipeline](https://github.com/ivanrsalazar/nft_pipeline)

An event-driven pipeline that reconstructs NFT sales from marketplace and
Ethereum activity and loads them into a PostgreSQL star schema.

- Captures OpenSea events through long-running WebSocket collectors
- Uses hourly S3 batches and Airflow for incremental processing
- Enriches transactions with Etherscan and Alchemy data
- Handles multi-NFT transactions at the individual sale grain
- Uses PySpark for historical block processing and Tableau for analysis

## What I am working toward

I am interested in analytics engineering, data analysis, business intelligence,
and data-platform operations roles where reliable pipelines and clear reporting
are both part of the job. I especially enjoy tracing quality issues to their
root causes and turning technical findings into concise, actionable insights.

## Connect

- [LinkedIn](https://www.linkedin.com/in/ivan-salazar-453344181/)
- [GitHub](https://github.com/ivanrsalazar)
