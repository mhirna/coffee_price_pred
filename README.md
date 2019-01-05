# coffee_price_pred

Coffee price - weather / currency rate dependency

### Key terms
ICO - International Coffee organization
Date format - DD-MM-YYYY
Coffee price - In US cents/lb of green coffee
Currency rate - USD based

### Data sources
- Daily coffee prices - http://www.ico.org/coffee_prices.asp 
- Daily currency rates to USD - https://apilayer.com/
- Countries that produce coffee - http://www.ico.org/historical/1990%20onwards/PDF/1a-total-production.pdf

For more info on specifics of prices look here: http://www.ico.org/documents/eb3776r1e.pdf

### Currency rate data
Is found in file “daily_currency_USD_base.csv” and consists of the following:
Date of the record.
… 169. Currency rate, named in format “USD” + name of currency

### Weather data
Is found in file “weather_data.csv” and consists of the following:
- totalSnow_cm - total snow (cm)
- maxtempC - max temperature (Celsius)
- mintempC - min temperature (Celsius)
- sunHour - hours of daylight during the day (hours)
- averageHumidity - average humidity during the day
- averageWindspeedKmph - average wind speed (km/hour)
- averagePressure - average pressure
- averageCloudCover - average cloud cover (%)

### Countries and cities
- Brazil, Sao Paulo
- Vietnam, Son La
- Colombia, Manizales
- Indonesia, South Sulawesi
- Ethiopia, Sidama
- Honduras, Copan
- India, Karnataka
- Uganda, West Nile
- Mexico, Chiapas
- Guatemala, Atitlan
- Peru, Chanchamayo
- Nicaragua, Jinotega
