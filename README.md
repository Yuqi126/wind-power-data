# Data Description
This dataset contains half-hourly wind power production records from 136 wind farms in Great Britain, covering the years 2021 to 2023. The key variables included are:

sd (Settlement Date): The date of the observation, formatted as YYYY-MM-DD.
sp (Settlement Period): Each day is divided into 48 half-hour periods. Days with daylight saving changes may have 46 or 50 periods.
wind_farm_id: A unique identifier assigned to each wind farm.
dtm: The timestamp of the measurement in UTC+0.
metered_power: The actual metered power output of each wind farm, in megawatts (MW), measured every half hour.
bav (Balancing Adjustment Volume): The amount of power the wind farm was instructed to reduce; non-zero values are excluded during preprocessing.

The file wind_generators.csv contains metadata for the wind farms, including:
Wind farm name
Latitude and longitude
Possibly capacity and operational status

The time series data is stored in three annual archive files: 2021.zip, 2022.zip, and 2023.zip.
