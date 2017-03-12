Metar Bitbar Plugin
---

Metar provides a simple Bitbar item to watch aviation weather for a specific airport. At a glance you can see what the conditions of your home airport.

Metar uses the same NOAA METAR data used for aviationweather.gov and checks for updates every 5 minutes.

# Requirements

  * Ruby >= 2.3.1
  * metar ruby gem
  * inifile ruby gem

# Setup

Inside the ~/.bitbarrc file is where you set the airport code you want to watch:

```
[metar]
airport=KDPA
```
