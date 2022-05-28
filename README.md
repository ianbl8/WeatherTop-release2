# WeatherTop: Release 2

This is **Release 2** of the WeatherTop web application, which meets the following criteria:

This builds on **Release 1**.

Implemented:
- **Readings**: Code, Temperature, Wind Speed, Wind Direction and Pressure fields are all used
- **Stations**: The station name and current readings are displayed for each station in a grid. This uses text terms for the weather, and displays the temperature in °C and °F, the wind speed in the Beaufort scale, the wind direction as a compass bearing, the wind chill in °C and °F, and pressure in hPa. A table listing all readings for the station appears below the grid.
- **Member**: Member class created with email, password, firstname and lastname fields, and stations.
- **Features**: Initial member details, station details and readings are read from `/conf/data.yml`. The Dashboard page displays a station list with folder buttons to open each station's page, and a section to add a new station (name only). The Station pages include a section to add readings for that station.
- **Code**: Files have been pushed to a Github repo using SmartGit (Sourcetree is sadly not available on Linux).

To implement:
- **Readings**: *all implemented*
- **Stations**: Maximum and minimum temperature in °C and °F, wind speed in km/hand pressure in hPa to be displayed.
- **Member**: Create login and signup pages.
- **Features**: Initial station details and readings are read from `/conf/data.yml`. The Dashboard page displays a station list with folder buttons to open each station's page, and a section to add a new station (name only). The Station pages include a section to add readings for that station.
- **Code**: Site to be deployed.
