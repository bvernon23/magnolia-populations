# Final Project: Magnolia Population Density in Ecuador

The title of my map is "Magnolia Populations in Ecuador". 

## Data 

I obtained the data set used in the creation of this map from the IUCN's website that allows free downloads of csv and polygon data of listed endangered species. There are 411 csv point values in the IUCN Red List data for magnolia species globally. I have included the data set on my repository titled "MAGNOLIAS_points". 

## Mapping process

After looking at the data distribution, I decided to display a smaller scope of magnolia populations. The country of Ecuador is a hotspot for this species, 310 of the csv values, and has lots of diversity through subspecies within the country. I have chosen to focus my map within Ecuador, and have used a heatmap display to show density amongst the different provinces. For the CRS of the map, I selected ESRI: 102033 (South America Albers Equal Area Conic).

## Creating the heat map

The portion of the map addressing the species density is the red heatmap icon. To create this portion I selected a radius of .3 degrees around each species location. These cirles stemming from each species then can over lap with each other, creating a lighter shade of the original fill color. The lighter the color indicates a greater species density in a given area. I also chose to lower the opacity of these heatmap circles so that viewers could see the individual species points beneath the symbology. 
