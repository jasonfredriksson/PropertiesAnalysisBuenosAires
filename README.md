# PropertiesAnalysisBuenosAires

An analysis of the values of the terrains of Buenos Aires, Argentina from 2001 to 2018. The data was gathered from the official site for the government of the Autonomous City of Buenos Aires (Federal Capitol of Argentina) on the following site: https://data.buenosaires.gob.ar/dataset/terrenos-valor-de-oferta

Initially, the data was grouped yearly, displaying only a single year per document. The information was filtered and grouped into a single Pandas Dataframe, from which it was possible to separate each of the districts of Buenos Aires and create a visualization for each, showing the progressive changes to the values of the Squared meter of terrain for each. 

The visualizations show a point for each of the terrains, sizing them according to the size of the terrain in squared meters (larger dots, larger terrains). Additionally, the minimum, maximum and mean value for the squared meter are represented.
