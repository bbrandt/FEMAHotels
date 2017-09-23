# FEMAHotels
Idea for scraping http://www.femaevachotels.com

* http://docs.python-requests.org/en/latest/
* https://www.crummy.com/software/BeautifulSoup/

# POST http://www.femaevachotels.com/index.php
* Content-Type: application/x-www-form-urlencoded
* raw: s_state=TX&submit=Find+Hotels

```
<div id="fullbox">
...
</div>
```
# FEMA ArcGIS Server
Data may more easily accesible here:
https://gis.fema.gov/arcgis/rest/services/FEMA

# Why?
Results are currently listed alphabetically, making locating a hotel near you difficult.

# Others
http://swamplot.com/your-map-to-the-houston-area-hotels-and-motels-where-fema-pays/2017-09-04/#comments
* Not all of TX
* Last updated 09/04/17 9:30am?
* Doesn't seem to update automatically
