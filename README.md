# US_hospital_Data_analysis

**About Dataset :**

This feature class/shapefile contains locations of Hospitals for 50 US states, Washington D.C., US territories of Puerto Rico, Guam, American Samoa, Northern Mariana Islands, Palau, and Virgin Islands. The dataset only includes hospital facilities based on data acquired from various state departments or federal sources which has been referenced in the SOURCE field. Hospital facilities which do not occur in these sources will be not present in the database. The source data was available in a variety of formats (pdfs, tables, webpages, etc.) which was cleaned and geocoded and then converted into a spatial database. The database does not contain nursing homes or health centers. Hospitals have been categorized into children, chronic disease, critical access, general acute care, long term care, military, psychiatric, rehabilitation, special, and women based on the range of the available values from the various sources after removing similarities.In this version any information contained in ADDRESS2 field found in earlier versions of this dataset has been merged with the ADDRESS field and the ADDRESS2 field has been deleted.In this update 75 additional records were added and the TRAUMA field was populated for 574 additional hospitals.

- TYPE : type of hospitals
- STATUS : status of hospital Open/Closed 
- TTL_STAFF : Total staff for each hospital
- TRAUMA : Level of trauma care that a hospital can provide
- COUNTY : Names of counties in which hospitals are located.
- COUNTYFIPS : Federal Information Processing Standards (FIPS) codes for the counties in which hospitals are located.
- COUNTRY : Names of countries in which hospitals are located.
- LATITUDE/LONGITUDE : Latitude and longitude coordinates of the hospitals.
- NAICS_CODE : North American Industry Classification System (NAICS) codes for the hospitals.
- NAICS_DESC : Description of the NAICS code for the hospital.
- SOURCE : Source of the data for the hospital.
- SOURCEDATE : Date on which the data for the hospital was collected.
- VAL_METHOD : Method used to determine the location of the hospital.
- VAL_DATE : Date on which the location of the hospital was determined.
- WEBSITE: Website address for the hospital.
- ALT_NAME: Alternate names for the hospital.
- ST_FIPS: FIPS code for the county in which hospital is located.
- OWNER: Owner of hospital. The owner may be a private company, a government agency, or a nonprofit organization.
- BEDS: Total number of beds in the hospital.
- HELIPAD: Indicates whether the hospital has a helipad or not.
