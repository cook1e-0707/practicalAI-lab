# Simple Lemonade Sales Data

`simple_lemonade_sales.csv` contains 30 fictional days at a lemonade stand.
The data is synthetic and is intended only for beginner teaching.

| Column | Meaning | Type |
|---|---|---|
| `temperature_f` | Daily temperature in degrees Fahrenheit | integer |
| `weekend` | `1` for a weekend and `0` for a weekday | integer |
| `cups_sold` | Number of cups of lemonade sold; this is the target | integer |

The values follow one simple teaching pattern:

```text
cups_sold = temperature_f - 40 + 10 × weekend
```

The one-input model uses only `temperature_f`. The two-input model uses both
`temperature_f` and `weekend`.
