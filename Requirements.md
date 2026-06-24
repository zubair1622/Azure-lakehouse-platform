# Functional Requirements

## Objective

Build an enterprise Azure Lakehouse platform capable of ingesting, transforming, and governing structured and semi-structured data.

---

## Data Sources

- CSV files
- XML files
- Dynamic JSON files
- SQL database tables

---

## Ingestion Requirements

- Support full load ingestion.
- Support incremental load ingestion.
- Convert all source files into Parquet format.
- Store data in ADLS Gen2.

---

## Security Requirements

- Store secrets in Azure Key Vault.
- Use Managed Identity.
- Avoid hardcoded credentials.

---

## Transformation Requirements

- Implement Bronze layer.
- Implement Silver layer.
- Implement the Gold layer.
- Use Delta Lake.

---

## Governance Requirements

- Implement Unity Catalog.
- Support RBAC.
- Enable data lineage.

---

## Orchestration Requirements

- Event-driven pipelines.
- Scheduled pipelines.
- Batch processing.
