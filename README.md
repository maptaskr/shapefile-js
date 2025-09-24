# Shapefile.js

Pure JavaScript library for parsing Shapefiles, returns Geojson projected into WGS84 lat lons.

See original package here:
https://github.com/calvinmetcalf/shapefile-js

This is a fork from the PR branch:
https://github.com/calvinmetcalf/shapefile-js/pull/225

with changes to help fix incorrectly wound polygons.

## About

Descended in a ship of theseus way from [RandomEtc's shapefile library](https://github.com/RandomEtc/shapefile-js) no code is shared.

- [World Borders shapefile](http://thematicmapping.org/downloads/world_borders.php) is CC-BY-SA 3.0.
- Park and Ride shapefile is from [MassDOT](http://mass.gov/massdot) and is public domain.
- MA town boundaries from [MassGIS](http://www.mass.gov/anf/research-and-tech/it-serv-and-support/application-serv/office-of-geographic-information-massgis/) and is public domain
- NJ County Boundaries from [NJgin](https://njgin.state.nj.us/NJ_NJGINExplorer/index.jsp) and should be public domain.
- [Proj4js](https://github.com/proj4js/proj4js) by me et al MIT
- Other test datasets copyright their respective owners.