## Dataset (NYC TLC Trip Records)

This project uses publicly available **NYC Taxi & Limousine Commission (TLC)** Yellow Taxi Trip Record Data in **Parquet** format.

### Files used (downloaded)
- `yellow_tripdata_2025-10.parquet`
- `yellow_tripdata_2025-11.parquet`
- `yellow_tripdata_2025-12.parquet`
- `yellow_tripdata_2026-01.parquet`
- `yellow_tripdata_2026-02.parquet`
- `taxi_zone_lookup.csv` (zone mapping table)

### Source
TLC Trip Record Data page: *(add link here)*  
Google Drive dataset folder (used in Colab): *https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page*

### Notes
Raw Parquet files are not uploaded to GitHub due to size limits. The notebook loads the files from Google Drive, then performs cleaning, hourly aggregation, EDA, feature engineering, forecasting, and peak-hour prediction.
