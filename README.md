# Neural Network Classification
Neural Network Classification on Bike sharing dataset using Tensorflow

## Dataset
[Dataset](https://archive.ics.uci.edu/ml/datasets/bike+sharing+dataset)
### Attribute Information:
Both hour.csv and day.csv have the following fields, except hr which is not available in day.csv
- instant: Record index
- dteday : Date
- season : Seasons 
    - 1: winter
    - 2: spring
    - 3: summer 
    - 4: fall
- yr : Year
    - 0: 2011
    - 1: 2012
- mnth : Month ( 1 to 12)
- hr : Hour (0 to 23)
- holiday : Weather day is holiday or not (extracted from [Web Link])
- weekday : Day of the week
- workingday : IF day is neither weekend nor holiday is 1, OTHERWISE is 0.
- weathersit :
    - 1: Clear, Few clouds, Partly cloudy, Partly cloudy
    - 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
    - 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
    - 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
- temp : Normalized temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-8, t_max=+39 (only in hourly scale)
- atemp: Normalized feeling temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-16, t_max=+50 (only in hourly scale)
- hum: Normalized humidity. The values are divided to 100 (max)
- windspeed: Normalized wind speed. The values are divided to 67 (max)
- casual: count of casual users
- registered: count of registered users
- cnt: Count of total rental bikes including both casual and registered
