# Kuala-Lumpur-bus-stops
Location of bus stops in the Klang Valley. Working in progress.

## Data sources
From [MyRapid Bus Kiosk](https://myrapidbus.prasarana.com.my/kiosk), select a route, enter source code (CTRL+U or add `view-source:` at the beginning of URL) and search for `var bstp =`, then copy everything on the same line after it, paste into JSON to CSV converter to convert to CSV file.

* File `rapidkl bus stop.csv` is the original data, initially obtained 8-11 July 2023 with an additional column showing data from which bus routes as well as the official bus stop code. (raw data straight from MyRapid Bus Kiosk)
* File `rapidkl bus stop compressed.csv` is the modified data where bus stops with the same id are combined and routes are shown all together, but currently still have some duplicates that needed to combine manually (especially MRT Feeder Bus routes). 
