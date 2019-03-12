# [Conservation Areas in South America](https://geo.gob.bo/geonetwork/srv/eng/catalog.search#/metadata/46bb6940-2f29-40bd-a330-64edd523a3e9)


The protected areas of South America and the world are the most valuable places for *in situ* conservation (Elbers, J, p.13). Accounting 34% of the world's plant species and 27% of mammals it is one of the world's biodiversity 'superpowers' (worldbank.org). The preservation of these treasure lands are very important due to the evident menace of man and its economic activities in the XXI century (Elbers, J, p.13). 

The World Database on Protected Areas (WDPA) is a joint project between the United Nations Environment Programme (UNEP) and the International Union for Conservation of Nature (UNEP-WCMC), in collaboration with governments, non-govermental organizations, academia and industry. The UN List is also incorporated into the WDPA. 

The WDPA includes a wide range of protected areas, including national protected areas recognized by the government, areas designated under regional and international conventions, privately protected areas and indigenous peoples' and community conserved territories and areas. The WDPA uses the IUCN and Convention on Biological Diversity (CBD) definitions of protected areas to determine wheather a site should be labeled as "protected area" in the WDPA.

The IUCN Protected Area Management Categories help classify protected areas based on their primary management objectives, while the IUCN Governance Types classify protected areas according to who holds authority, responsibility and accountability for them. 

![IUCN.pgn]
Fig. 1 IUCN Protected Area Management Category and Governance Type

With the creation of these maps I want to emphasize the value and importance of the protected areas for South America and the world.

The World Database on Protected Areas (WDPA) is stored as a file geodatabase comprising two datasets and one source table (metadata). 

*  Two feature classes: one with polygons and with points; both with associated spatial and tabular information of protected areas key attributes. 

*  One source table: the WPDA source table describes the source of the data in the WDPA, containing information on the data provider, currency of dataset and other metadata.

The WDPA ID is the globally unique identifier for each protected area in the WDPA and as such acts as the parent identifier of the database. Different designations of protected areas may occupy the same geographical space in which case each of these will have a different WDPA ID. 

#### Spatial Data

The WDPA is based on the Geographic Coordinate System: World Geodetic Survey (WGS) 1984. Each protected area in the WDPA is either represented as a polygon boundary, or if unavailable, a point location.

*   Polygon Data

Polygon data represents the boundary of the protected area. A polygon may be single-part, or multi-part, where there are multiple non-connecting parts associated with the same protected area. A multi-part polygon accounts for only on WDPA ID in the attribute table.

*   Point Data

Where boundary data is unavailable, the latitude and longitude of the centermost point of the site is requested as a reference point for the protected area instead.

#### Attribute Data

The WDPA data attributes are the tabular fields associated to the WDPA point and polygon features. 

## Data

The data was obtained from the catalogue [Protected Planet](https://protectedplanet.net/c/unep-regions#Latin%20America%20&%20Caribbean)

<!-- GeoBolivia: [Mapa Área de Conservación Suramerica COSIPLAN, 2015](https://geo.gob.bo/geonetwork/srv/eng/catalog.search#/metadata/46bb6940-2f29-40bd-a330-64edd523a3e9) -->

## Project Goals

1. Create a thematic map with Conservation Areas in South America.
2. Create a base map with Carto.
3. Create an interactive map with data visualization of each country.
