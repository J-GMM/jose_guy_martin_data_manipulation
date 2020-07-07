# jose_guy_martin_data_manipulation
 Data manipulation notebooks and scripts written and used by Jose-Guy Martin.

## Singe United States Airline
Workbook that combine tables of destinations reached by several airlines into a single table, which is then used to generate a map of destinations.

`airline_destination_data` workbook completes the following steps:
* Combines separate airline tables into a single table of desinations, showing only airport ICAO code.
* Joins airline destinations with a table containing name and coordinate data of all airports.
* Creates a table of airports with columns showing which airline reaches each airport (Y/N).

The resultant table is then fed into QGIS to produce the attached map, showing each airport by how many airlines reach said airport. 

A column named `Weight` was added to the Y/N table, noting hubs and focus cities of each airline.

Several label rules were applied for readability, noted in label_rules.txt.

![Destinations USA](/airline_destinations/airline_destinations_usa.png)

Additional maps and .qgis file will be uploaded soon.