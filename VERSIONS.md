# Course versions — System Design для Data Engineer

Last review: 2026-04-30
Next review: 2027-04-30

## Cadence

Годовой — курс синтезирует архитектурные паттерны (lakehouse, streaming, CDC, governance), опираясь на baseline-курсы (kafka-course, spark-course, storage-formats, debezium-course, data-governance). Конкретные версии живут в этих курсах; здесь фиксируется синтез на момент ревью.

## Pinned baseline (April 2026)

| Component | Version | Released | Course depth |
|-----------|---------|----------|--------------|
| Apache Airflow | 3.0 | 2025-04 | full |
| Apache Flink | 2.0 | 2025-03 | full |
| Apache Kafka | 4.0 | 2025-03 | full (через kafka-course) |
| Apache Spark | 4.0 / 4.1 | 2025+ | full (через spark-course) |
| Apache Iceberg REST catalog (Polaris) | GA | 2025+ | partial |
| Unity Catalog OSS | stable | 2025+ | partial |
| Lakekeeper (Iceberg REST) | OSS | 2025+ | mention |
| Apache Iceberg | V3 | 2025-06 | full (через storage-formats) |
| Delta Lake | 4.0 / 4.1 | 2025+ | partial (через storage-formats) |
| Debezium | 3.4.x | 2026-01 | full (через debezium-course) |
| OpenLineage | 1.x | 2026 | partial |
| dbt Core / Cloud | 1.9+ | 2026 | partial |
| Dagster / Prefect (альтернативы Airflow) | stable | 2026 | mention |

## Forthcoming (next review)

- Airflow 3.1 / 3.2 — task isolation и DAG processor v2.
- Flink 2.1 — disaggregated state для streaming lakehouse.
- Iceberg V4 концепты (если появятся) и evolution V3 deletion vectors / row lineage.
- Lakehouse storage triad: Iceberg / Delta / Hudi — обновлённое сравнение и BYO-catalog.
- Streaming SQL convergence: Flink SQL vs Spark Structured Streaming vs ksqlDB.

## Recent updates

- 2026-04-30 — Wave 1 P0 правки (Airflow 3.0, Flink 2.0, REST catalogs) + Wave 2 новые уроки (Polaris/Unity OSS/Lakekeeper, Iceberg V3 в lakehouse) + Wave 3 cross-refs во все baseline-курсы.
