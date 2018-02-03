# OSM4GIS
A physical representation of the OenStreetMap (OSM) Features in a GIS ready format, with layers categorized according to OSM article: (https://wiki.openstreetmap.org/wiki/Map_Features#Primary_features).

The layers attributes have been modeled and normalized to a standard schema to make them consistent for the use of GIS Analysts to query, and create definition queries, and apply symbology while creating their beautiful maps.

The repositories are categorized based on world region then choose the content for specific country to download.

The intention is to keep the data up-to-date.
Currently, the data is updated on a weekly basis (every Friday).

To make the data ready to use, the data has been exported into KML format,in Geographic WGS84 coordinates system.
In future it will be available in other GIS Open formats such as OGC GeoPackage.


```
Map Feature				Area						Line								Point
                                                                                
Aerialway:			aerialway_area					aerialway_line			aerialway_point
Aeroway:			aeroway_area				aeroway_line				aeroway_point
Amenity:			amenity_area											amenity_point
Barrier:										barrier_line			barrier_point
Boundary:			boundary_area				 boundary_line	
Building:			building_area										building_point
Country:			country_area		
Craft:				craft_area								craft_point
Electoral:			electoral_area		
Emergency:			emergency_area								emergency_point
Geological:			geological_area								geological_point
Highway:			highway_area				highway_line			highway_point
Historic:			historic_area				historic_line			historic_point
Island:				island_area				island_line				island_point
Landuse:			landuse_area									landuse_point
Leisure:			leisure_area				leisure_line				leisure_point
Man_made:			man_made_area					man_made_line			man_made_point
Military:			military_area					military_line			military_point
Natural:			natural_area					natural_line			natural_point
Office:				office_area									office_point
Place:				place_area							place_point
Power:				power_area				power_line				power_point
Protected_area:			protected_area		
public_transport:		public_transport_area		public_transport_line		public_transport_point
Railway:				railway_area					railway_line				railway_point
Route:									route_line	
Shop:				shop_area										shop_point
Sport:				sport_area				sport_line				sport_point
Tourism:			tourism_area				tourism_line				tourism_point
Waterway:			waterway_area				waterway_line				waterway_point
```