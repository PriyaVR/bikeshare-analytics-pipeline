# bikeshare-analytics-pipeline
End-to-end Databricks + Power BI pipeline analyzing Toronto Bike Share ridership and weather patterns.

# Bike Share Toronto Analytics Pipeline

End-to-end data pipeline: Databricks (bronze/silver/gold) + Power BI reporting.

## Data Sources
- Bike Share Toronto Ridership Data (2025, 12 months, ~7.8M trips)
- Open-Meteo Historical Weather API (365 days, Toronto)

## Status
- ✅ Bronze layer: raw trips and weather loaded as Delta tables
- ✅ Silver layer: cleaning, deduplication, weather join
- ✅ Gold layer: star schema (dim_date, dim_station, dim_user_type, fact_trips)
- ⏳ Power BI: DAX measures and report
