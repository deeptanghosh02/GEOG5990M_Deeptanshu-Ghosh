# Background/Context of the Project
The emergence of short-term rental platforms like AirBnB has dramatically reshaped the structure of cities, with increasing concerns regarding affordability challenges, tourism pressures and gentrification in UK cities (Wachsmuth and Weisler 2018). In the meantime, public health experts use indicators like the Access to Healthy Assets and Hazards (AHAH) Index to assess how healthy various neighbourhoods are based on their proximity to amenities, air quality, and environmental factors.

The aim of this project is to explore the relationship between AirBnB prices per night by listing and neighbourhood health environments in Bristol, UK as measured by AHAH Index percentile which is a proxy for area-level wellbeing. Exploratory data analysis revealed that there was no statistically significant relationship between neighbourhood health and AirBnB pricing, leading to a narrow examination of the distribution of average daily prices across Lower Super Output Areas in Bristol. Bristol was chosen as the right case study due to its high tourism economy and documented housing pressures (Bristol City Council, 2023).

# Repository Contents
GEOG5990M_Final_Project.ipynb - Main Jupyter Notebook containing all code, analysis and markdown.

airbnb_data_bristol.csv- AirBnB listings data for Bristol (2,556 listings, 28 columns)

bristol_ahah_index.geojson - AHAH index data at LSOA level for Bristol (263 LSOAs)

# What the Code Does
The code loads the two datasets and does some initial data cleaning on the two datasets - the Bristol AirBnB listings dataset and the AHAH entry neighbourhood healthiness index dataset. Then it merges those by LSOA to see how much each neighbourhood's average per night price was. It then runs a Spearman's rank correlation to check if higher priced AirBnB regions were associated with healthier neighbourhoods or unhealthier neighbourhoods.Lastlt 2 visualisations are shown: (1) horizontal bar chart comparing median AirBnB per night prices by room type; (2)a side-by-side choropleth map showing health services access and average Airbnb prices across Bristol LSOAs. 
