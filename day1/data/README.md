# Moon Crystal Sales Data

`moon_crystal_sales.csv` contains 12 fictional days at a crystal shop on
the Moon. The data is synthetic and is intended only for teaching.

| Column | Meaning | Type |
|---|---|---|
| `visitor_shuttles` | Number of visitor shuttles that arrived | integer |
| `light_shows` | Number of light shows held that day | integer |
| `crystals_sold` | Number of crystals sold; this is the prediction target | integer |

The values contain a simple fictional pattern for students to discover. The
first model uses only `visitor_shuttles`. The second model uses both
`visitor_shuttles` and `light_shows`.
