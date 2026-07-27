# Day 1 Data

`bluebikes_june_2025.csv` contains 30 days of real Cambridge Bluebikes
trip counts and Boston weather observations from June 2025.

| Column | Meaning | Type |
|---|---|---|
| `date` | Calendar date | text in `YYYY-MM-DD` format |
| `temperature_f` | Daily mean temperature at Boston Logan International Airport, in degrees Fahrenheit | decimal number |
| `weekend` | `1` for Saturday or Sunday and `0` for Monday through Friday | integer |
| `bike_trips` | Bluebikes trips that started or ended in Cambridge that day | integer |

The values are observed data, not fictional sales values and not a perfectly
straight pattern. Temperature and the day of the week may help explain trip
counts, but many other factors can also affect how many trips people take.

## Sources

- Daily trip counts: [Cambridge Open Data — Bluebikes Data Summarized](https://data.cambridgema.gov/Transportation/Bluebikes-Data-Summarized/cc2f-bntg/about_data)
- Daily temperature: [NOAA Global Summary of the Day — Boston Logan International Airport, 2025](https://www.ncei.noaa.gov/data/global-summary-of-the-day/access/2025/72509014739.csv)

The Cambridge table is published under the Open Data Commons Public Domain
Dedication and License. The NOAA file identifies station `72509014739` as
Boston Logan International Airport.

## How This Teaching File Was Prepared

1. Keep the Cambridge daily trip totals from `2025-06-01` through
   `2025-06-30`.
2. Match each date with NOAA's `TEMP` value for the same date.
3. Rename `TEMP` to `temperature_f`.
4. Create `weekend`: Saturday and Sunday are `1`; all other days are `0`.
5. Keep only the four columns shown above.

The one-input model uses only `temperature_f`. The two-input model uses
`temperature_f` and `weekend`. The target is `bike_trips`.
