# Dataproject


In this data project we are examining whether there are any correlation between unemployment rates and fertility rates on a municipality level in Denmark in the years from 2007 until 2017. First we download the tables of interest from Denmark Statistics (DST), (using API) and then merge them into a combined dataset. We are importing FOD407 which contains information about the fertility rate for each municipal in Denmark, and we also extract data from AULP01 which has information regarding the unemployment rate in Denmark on a municipality level as well. 
Utilizing this combined dataset we do some graphical explorations of the evolution of the unemployment rate and the fertility rate and the correlation between the two. Specifically, we are presenting a map showing the fertility rate and the unemployment rate for each municipal in 2007 and 2017. Furthermore, we are showing a figure where the two variables are indexed. This graph is an interactive figure where the development for both the fertility rate and the unemployment rate can be explored for each municipal in the timeline 2007-2017.


In order for the project to work it is important that the API and GeoPandas packages are downloaded. Further, the shape files containing the map we are using should be downloaded from the repository in order to make the map visible.  

