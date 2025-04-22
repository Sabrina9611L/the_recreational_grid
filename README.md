# The Recreational Grid 

# Executive Summary
In this capstone project, I want to look at a variety of data to explore the accessibility, equity, and quality of outdoor recreation across Tennessee. Using geospatial and demographic data, the project identifies underserved communities, evaluates the physical and environmental features of existing recreational infrastructure, and offers data-driven recommendations for expanding access to parks and trails. 

# Motivation
As someone who loves to hike, I wanted to explore Tennessee's trail data. This lead me to also look into community inequality, by this I mean I quickly noticed that not all communities have the same level of access to parks, trails, and recreational space. 

I’ve always believed that access to nature and outdoor spaces shouldn’t depend on where you live or how much you make. I wanted to use data to uncover where the gaps are, who’s being left out, and how we can make smarter decisions about where to invest in trails and parks.

My goal was to understand how accessible outdoor recreation is in Tennessee and where future investments should be prioritized.

# Data Questions
"How accessible is outdoor recreation in Tennessee, and where should future trail or park investments be prioritized?"

"Can we rank zipcodes for trail expansion priority?"

"Are there rail segments that run near parks or residential areas that are inactive and could be repurposed?"

"Where are the largest trail gaps between parks, trails, and residential areas?"

"Which zipcodes have high public land density but low population density?"

"How much of each zipcode is covered by recreational infrastructure?"

"Are there trail deserts (zipcodes or areas with no trails within 1 mile)?"

"Which zipcodes have the longest total trail length?"

"Do lower-income or rural zipcodes make fewer reservations?"

"Which zipcodes generate the most outdoor reservations?"

"How does median income vary across zipcodes with high vs. low recreation access scores?"

# Minimum Viable Product (MVP)
I want to deliver a reproducible spatial analysis of outdoor recreation access across Tennessee, highlighting underserved areas and prioritizing where new parks or trails could be developed.

# Data Sources
•	Tennessee Transportation (GPKG)
https://prd-tnm.s3.amazonaws.com/StagedProducts/Tran/GPKG/TRAN_Tennessee_State_GPKG.zip

•	TN State Parks Points
https://gis.tnstateparks.com/datasets/d4ef724303da4619ba2972e00e716f03_0/explore

•	TN Public Trails
https://gis.tnstateparks.com/datasets/d67ab502132f4b12ac2c1ab34eb8cac6_0/explore

•	TN Public Parks (API)
https://services1.arcgis.com/YuVBSS7Y1of2Qud1/arcgis/rest/services/Tennessee_Statewide_Trails_Lines_Public/FeatureServer/0/query?where=1%3D1&outFields=*&outSR=4326&f=json

•	USGS Elevation (EPQS)
https://apps.nationalmap.gov/epqs/

•	USGS ScienceBase Geodata
https://www.sciencebase.gov/catalog/item/62a96b9bd34ec53d2770f2c0

•	Protected Areas/Trail Data
https://www.sciencebase.gov/catalog/item/652d4f80d34e44db0e2ee45c

•	Recreation.gov Facility Data (RIDB)
https://ridb.recreation.gov/download

•	Census Data Access
https://data.census.gov/

•	US Census API Signup
https://api.census.gov/data/key_signup.html


# Known Issues and Challenges
I know that with the amount of data I have gathered, I will be able to do a thorough analysis. I also recognize that there will be many struggles cleaning the data and ensuring compatibility. The data I had initially opted to use, was not a viable option and I am hoping that this new data will lend to a robust and fruitful capstone project.
