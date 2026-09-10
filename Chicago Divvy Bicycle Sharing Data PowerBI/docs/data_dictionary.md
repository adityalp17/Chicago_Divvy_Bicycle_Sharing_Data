# Data Dictionary

Fields used in the Power BI data model (table: `data`). Update descriptions/types to match your actual CSV.

| Field | Description | Type |
|---|---|---|
| `trip_id` | Unique identifier for each trip | Integer / Text |
| `from_station_id` | ID of the station where the trip started | Integer |
| `from_station_name` | Name of the starting station | Text |
| `to_station_id` | ID of the station where the trip ended | Integer |
| `to_station_name` | Name of the ending station | Text |
| `start_time` | Timestamp when the trip started | Date/Time |
| `stop_time` | Timestamp when the trip ended | Date/Time |
| `tripduration` | Duration of the trip, in seconds | Numeric |
| `usertype` | Rider type — e.g. `Member` or `Casual` | Text |
| `gender` | Rider gender, if reported | Text |
| `temperature` | Recorded temperature for that day/hour | Numeric |
| `events` | Weather condition (e.g. clear, rain, snow) | Text |
| `latitude` / `longitude` | Coordinates of the start station, used for the map visual | Numeric |

> ✏️ Add or remove rows so this matches your actual CSV column headers exactly.
