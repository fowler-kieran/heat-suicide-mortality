## Heat and Suicide Mortality in the United States
This map combines HTML, CSS, JS, and Leaflet libraries to create a final product that highlights the link between extreme temperatures and suicide mortality in the contiguous United States.


The finished map is a bivariate map that combines choropleth symbology for average mean surface temperatures and qualitative point data. In terms of interactivity, map users can click on the skull icon for each state to receive information about the mortality rate of that state. It is meant to be a companion piece for the story published by Stanford News about heat and suicide, which is viewable from this [link](https://news.stanford.edu/2018/07/23/warming-temperatures-linked-increased-suicide-rates/).

### Data Sources
- Average Temperature Data from NOAA
- Suicide Statisitics from the CDC
- GeoJSON conversion acquired from geojson.io
- Color palettes sourced from ColorBrewer2
- Map icons provided by Font Awesome

### Methods
After much deliberation, I decided that a bivariate symbol map would be the best decision, according to my abilities. The first step was to compile all the necessary data into excel sheets. For my temperature data, I joined it to a shapefile of the US, and exported it as a geoJSON in QGIS. The suicide data was joined with the lat/long coordinates for the geographic center of every state, and the whole table was converted to a geoJSON using geojson.io. Once both of my assets were ready, I created a new project in Atom, and compiled all my code to create the finished product. I ran into a lot of difficulty trying to implement other levels of interactivty throughout the process, so ultimately I settled on just have an interactive tooltip for the suicide data.


#### Final Thoughts
Though this map is pretty different from my intital idea, I am still very pleased with the final result. I am especially glad to have it included in my portfolio.
