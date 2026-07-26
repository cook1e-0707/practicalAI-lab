# Lemonade Sales data

`lemonade_sales.csv` contains 72 fictional days of lemonade-stand observations.
It is synthetic and is intended only for teaching.

| Column | Meaning | Type |
|---|---|---|
| `temperature_f` | Daily temperature in degrees Fahrenheit | integer |
| `weekend` | `1` for Saturday/Sunday, otherwise `0` | integer |
| `rain` | `1` if it rained, otherwise `0` | integer |
| `cups_sold` | Number of cups sold that day; this is the prediction target | integer |

The data includes random variation, so no model predicts every day perfectly.
The dataset has no missing values. A fixed split (`random_state=42`) is used in
the lab so all students can compare results.
