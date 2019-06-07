# Digging-In-Community-Garden-Data
Digging In is a data repository that houses community garden data for use and reuse by policy makers, researchers, and the public.
This protocol normalizes four data sources as an example of best practices for Digging In community garden data. See the DATA DICTIONARY for a full list of variables, their human-readable labels, allowed values, and definitions. Variables with a YES under the REQUIRED column in the data dictionary will be present in all datasets and will be normalized to the front of each dataset.

Each file uses the naming schema of their original source. Please review dataset records within the Digging In repository for standardized file names for existing datasets.

NYC_GREENTHUMB_COMMUNITY_GARDENS was a robust dataset. A number of variables were removed during the normalization process because they were too specific to be generalized to the entire USA.

GARDEN_CITY_HARVEST_COMMUNITY_GARDEN_LIST was a far less structured dataset and required a great deal of transformation during the normalization process. 

PPATCHES was determined a viable dataset given it’s breadth of information and already clean nature. County specific variables were removed due to scope of protocol; added variables contain N/A attributes throughout the column. Largest transformation occurred within DEPT variable where accessible abbreviations were expanded to facilitate reuse.

DC_COMMUNITY_GARDENS underwent a large transformation process; several required variables weren’t present and many were missing data. Furthermore, there were three separate variables for Latitude and Longitude attributes which were paired down to one. Concerns regarding contact-based data arose as it relates to consistency and reuse within the datasets.
