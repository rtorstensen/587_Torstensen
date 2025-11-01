This readme file was generated on 2025-11-01 by Riley Torstensen
GENERAL INFORMATION
⦁	Title of Dataset: Measuring Community Access to Light Rail Transit Stations: Green Line Impact
⦁	Purpose: The purpose of this project is to assess the accessibility of Calgary’s Light Rail Transit (LRT) system by analyzing the ease of travel from each community to its nearest station.
⦁	This map is projected in Projected Coordinate System	Calgary_3TM_WGS_1984_W114
⦁	The Geographic Coordinate system for the results is in WGS_1984.

Author Information
Name: Riley Torstensen
ORCID:30184881
Institution: University of Calgary	
Email: riley.torstensen@ucalgary.ca

DATA & FILE OVERVIEW
File List:
⦁	Community Boundaries
⦁		Sourced from Open Calgary
⦁		Community District Boundaries for the City of Calgary. 
⦁		Date accessed: 2025-11-01
⦁	Green Line Stations
⦁		Sourced from Open Calgary
⦁		Stations as depicted on the Green Line Map. Station locations 		approved by Council in 2017 June, but subject to change based on 	Green Line LRT design reviews.
⦁		Date accessed: 2025-11-01
⦁	LRT Stations
⦁		Sourced from Open Calgary
⦁		Red and Blue Line LRT Stations, providing access to the light rail 	network for commuting and travel

METHODOLOGICAL INFORMATION
⦁	Collection methods: Downloaded layers as shapefiles and imported into ArcGIS Pro
⦁	Processing: calculated distances from community centroids

Methods for processing the data:
A line was drawn between the Green Line Stations signifying the Green Line LRT route. 	
A buffer was created around the Green Line LRT with a 3km radius. 
OD Cost Matrix was conducted setting the Destinations as the Green Line LRT Stations and the Starting Points as each Community Centroid

