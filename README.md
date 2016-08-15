# pluto-max-far
PostGIS workflow for calculating max FAR for all BBLs based on special purpose districts and subdistricts

##About
[MapPluto](http://www1.nyc.gov/site/planning/data-maps/open-data.page) contains various allowable FAR columns based on a tax lot's zoning, but doesn't include the additional FAR that may be allowed based on lot's location in a Special Purpose District.  This workflow joins parcels with the special purpose districts and calculates the max allowable FAR based on district and subdistrict.  

Essentially we are calculating two new attribute columns: `columna` - explanation of column a, and `columnb` - explanation of column b

##Methodology
This is based on bbls. 
##Data Sources

##Queries

##Output
The following CSV is available in this repo based on the latest workflow.
