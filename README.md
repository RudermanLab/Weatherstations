# Weatherstations

Metadata about weather stations worldwide

## Identifier conversion - weather_station_crossref.csv

This comma-separated-values file contains cross referencing
information between identifiers and some basic metadata around weather
stations. Information in this file was distilled from the files found
in http://berkeleyearth.lbl.gov/auto/Stations/TAVG/Text/* from the
Berkeley Earth project (http://www.berkeleyearth.org/).

### Columns

* berkeley.id - The unique numeric ID of the station assigned by the
Berekeley Earth project.
* name - Station name
* country - Location country of station
* latitude - Station latitude
* longitude - Station longitude
* elevation.m - Station elevation in meters
* WMSSC - World Monthly Surface Station Climatology identifier(s)
* WMO - World Meteorological Organization identifier(s)
* GHCND - Global Historical Climatology Network identifier(s)
* GSOD - Global Surface Summary of the Day identifier(s)
* ICAO - International Civil Aviation Organization identifier(s)
* USAF - United States Air Force identifier(s)
* GHCNM - Global Historical Climatology Network Monthly identifier(s)
* HADCRU - Met Office Hadley Centre for Climate Science and Services
identifier(s)
* NCDC - NOAA National Climatic Data Center identifier(s)
* WBAN - Weather Bureau Army Navy identifier(s)
* FAA - Federal Aviation Administration identifier(s)
* WWR - World Weather Records identifier(s)
* COOP - Cooperative Observer Network identifier(s)
* CA - ?
* NWS - National Weather Service identifier(s)

```
There may be multiple identifiers from a given source. When this
occurs, the identifiers will be separated by the pipe symbol
"|". According to the Berkeley Earth web pages, this can happen when
"identification of the station changed during its history or if two
different records were found to contain the same data, in which
case the records would be merged."
```

## Contributing

Please email any corrections or suggestions to ruderman@usc.edu

## Authors

* **Dan Ruderman** (ruderman@usc.edu)

## License

The authors of these materials grant permission (free of charge) to
authors, readers and third parties to reproduce their materials as
part of another publication or entity with proper sourcing to Dan
Ruderman and by additionally providing a link to this GitHub repository
(https://github.com/RudermanLab/Weatherstations).


## Acknowledgments

* Primary data were provided by the Berkeley Earth project (http://www.berkeleyearth.org)


