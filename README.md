# chhs-geojson
## Using the CHHS open data along with GeoJSON

This is just playing around prototpying the use of the State of California's open data:

(https://chhs.data.ca.gov/Facilities-and-Services/Community-Care-Licensing-Foster-Family-Agency-Loca/v9bn-m9p9)[https://chhs.data.ca.gov/Facilities-and-Services/Community-Care-Licensing-Foster-Family-Agency-Loca/v9bn-m9p9]

This is being carried out under contract for CivicActions as part of our participation for:

RFI #75001, Agile Development Pre-Qualified (ADPQ) Vendor Pool

But note: This is released under Creative Commons.  Anybody, including other bidders applying to the RFI, are free to use this code.

## Limitations

This was hacked together very quickly.

It has many weaknesses:

* The text listing just uses JSON.stringify, obviously that is not meant to be a UI for humans.
* There is no error handling for if you enter a zip code that is not in the CHHS database
* There seem to be other data problems (misformed data) that are not handled robustly.
* I use the "cafe" symbol, which is weird, but it was hard to find one that looks like a nice house for kids.
* Zoom level has zero intelligence.
* I'm adding each feature in its own layer which is almost certainly wrong.




