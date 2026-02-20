In this project the aim is to demonstrate how vibe coding can improve the accessibility and transparency of ecological research. 
Therefore we demonstrate how to create an interactive web tool to visualize the global catalogue of biome classifications (Fischer et al., 2022). 


Before starting to build an application, it is important to be clear which kind of data and which functionalities the application should include. 
The data in our example for the global biome inventory is a spatial raster stack.  

Furthermore, we define the purpose and the target group from the very first start: 
The biome inventory should stay simple, with a dropdown menu to select single biome maps, a legend and additional metadata information. 
The aim should be to give a quick overlook of the distribution and metadata of the global biomes, hence interested researchers have a tool to evaluate the data, get the differences between the biome maps and choose suited ones for their projects. 

There are plenty possibilities to realize a project like this (e.g. Shiny or Leaflet). We choose to build a webmap based on MapLibre, embedded in a HTML, JavaScript Homepage.
This way it can be published easily via Github pages and the MapLibre library has a good support for raster maps and global visualizations.



The original dataset from Fischer et al. (2022) is stored in the data_origin folder.

Processed data for the visualization is then stored in the data folder.

Rscripts for preprocessing data are to be found in the Rscripts folder.



Citation:

Fischer J-C, Waltenowitz A, Beierkuhnlein C (2022) The biome inventory - Standardizing global biogeographical units. Global Ecology and Biogeography31(11):2172-2183: https://doi.org/10.1111/geb.13574 For the compilation of the biome layers.

Groß H, Zizka A (2025): biomes: Analysis of Taxon Distributions in Global Biomes. R package, Version 0.9. https://github.com/azizka/biomes. For the Rpackage.
