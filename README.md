# forecast.io Weather

CLI to get weekly forecast from forecast.io

You will need an API key from https://developer.forecast.io/
It's free for 1000 API calls per day.

Can add it to your environment variable or just paste it in for the value of `forecast_api_key`

## Options
- Get location from your ip address
- Enter location manually, zip or city, state

Just comment out / delete the option that you don't want to use.

__Units__
- Set `units = ` "us" for °F or "si" for °C

### To run:
- `git clone https://github.com/dhcrain/forecast.io_weather.git`
- `pip install requirements.txt`
- `python forecast.py`


Tested in Python 3.5.1 / OSX
Powered by Dark Sky - https://darksky.net/poweredby/
