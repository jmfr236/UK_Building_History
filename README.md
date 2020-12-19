# UK_Building_History
Interactive map showing the building construction(or acquired) history of University of Kentucky Buildings. 

GitHub Page URL: https://jmfr236.github.io/UK_Building_History/ 

# Topic & Geographic Phenomena 
<b><u>Title</u></b>: University of Kentucky Building History (1865-2020) | Campus Expansion through the Decades

<b><u>Project Topic</u></b>: Display University of Kentucky Buildings by year constructed/acquired from the establishment of the University (1865) to present day. Will also identify by type of building (Housing, Academic, Med Center, Athletic, Other). 

<b><u>Objectives</u></b>: Show campus growth and housing/amenity trends on the University of Kentucky Campus from its establishment in 1865 to today.

<b><u>User Needs</u></b>: Map would be most useful by Facilities Personnel and Administration, but also folks interested in the history of UK campus and expansion would also enjoy looking at this map. So this map would need to be easy enough for someone with limited technological experience to navigate, but also engaging enough for someone with more experience. Folks with less mapping experience would be able to still easily view campus construction through the decades to reference when buildings were built or acquired, but more detail can also be shown by applying filters by building function type. Would also like the map to function well on desktop and mobile for facility personnel in the field.

<b><u>Data Source</u></b>: UK Building information and data is provided by UK ITS Information Services - Geospatial Team. 

<br>

# Function & Design

<b><u>Map Features</u></b>: Map will display polygon building features. Functions will include a time slider based on the year constructed (if constructed year is unknown will be based on acquisition date), a drop down selection to filter based on building type (Housing, Academic, Med Center, Athletic, Other) to help identify trends with more detail. Pop up will display showing the building name, address, usage area, year constructed, year acquired, and a photo of the building. 

<b><u>Technology Stack</u></b>: For data processing used QGIS for conversion of GIS shapefiles into geojson files with Web Mercator projection. Basemap will be pulled from mapbox Studio using Monochrome Sky to mimic the appearance of a blueprint. Utilize leaflet and jquery plugins for javascript and site development. Site style will follow UK branding colors. Web map will be hosted using GitHub Pages.
