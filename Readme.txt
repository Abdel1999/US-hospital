About Dataset :

This feature class/shapefile contains locations of Hospitals for 50 US states, Washington D.C., US territories of Puerto Rico, Guam, American Samoa, Northern Mariana Islands, Palau, and Virgin Islands. The dataset only includes hospital facilities based on data acquired from various state departments or federal sources which has been referenced in the SOURCE field. Hospital facilities which do not occur in these sources will be not present in the database. The source data was available in a variety of formats (pdfs, tables, webpages, etc.) which was cleaned and geocoded and then converted into a spatial database. The database does not contain nursing homes or health centers. Hospitals have been categorized into children, chronic disease, critical access, general acute care, long term care, military, psychiatric, rehabilitation, special, and women based on the range of the available values from the various sources after removing similarities.In this version any information contained in ADDRESS2 field found in earlier versions of this dataset has been merged with the ADDRESS field and the ADDRESS2 field has been deleted.In this update 75 additional records were added and the TRAUMA field was populated for 574 additional hospitals.

Features explanation :

-X ,Y :The main coordinates of hospitals
-NAME :The name of hospitals
-ADDRESS :The hospital adress
-CITY : Cities in which hospitals are located
-STATE : different US states in which hospitals are located
-ZIP/ZIP4 : Zip code
-Telephone : Tel numbers of hospitals
-TYPE : type of hospitals
-STATUS : status of hospital Open/Closed 
-TTL_STAFF : Total staff for each hospital
-TRAUMA : Level of trauma care that a hospital can provide
-COUNTY : Names of counties in which hospitals are located.
-COUNTYFIPS : Federal Information Processing Standards (FIPS) codes for the counties in which hospitals are located.
-COUNTRY : Names of countries in which hospitals are located.
-LATITUDE/LONGITUDE : Latitude and longitude coordinates of the hospitals.
-NAICS_CODE : North American Industry Classification System (NAICS) codes for the hospitals.
-NAICS_DESC : Description of the NAICS code for the hospital.
-SOURCE : Source of the data for the hospital.
-SOURCEDATE : Date on which the data for the hospital was collected.
-VAL_METHOD : Method used to determine the location of the hospital.
-VAL_DATE : Date on which the location of the hospital was determined.
-WEBSITE: Website address for the hospital.
-ALT_NAME: Alternate names for the hospital.
-ST_FIPS: FIPS code for the county in which hospital is located.
-OWNER: Owner of hospital. The owner may be a private company, a government agency, or a nonprofit organization.
-BEDS: Total number of beds in the hospital.
-HELIPAD: Indicates whether the hospital has a helipad or not.

Questions :2-How many hospitals provide trauma care? What is the distribution by state or city?
	   3-What are the predominant types of hospital owners (private, government, nonprofit)? How does ownership vary by state?
	   4-Do certain types of hospitals (e.g., nonprofit) have more beds than others?
	   5-How does the presence of a helipad correlate with the hospital's bed count or other factors?
	   6-How many hospitals have listed websites? What is the distribution by state?
	   7-Which states or cities have the highest and lowest bed capacities?














NAICS CODE : The North American Industry Classification System (NAICS) is a system for classifying business establishments by their economic activity. It is used by the United States, Canada, and Mexico to collect, analyze, and publish statistical data related to the business economy.

A NAICS code is a six-digit number that identifies a specific industry. The first two digits of the code represent the sector of the economy, the second two digits represent the subsector, and the last two digits represent the industry group.

Country Fips : eg. US: United States ,CA: Canada ,MX: Mexico ,CN: China


TTL_STAFF : stands for Total Staff. It is a variable in the US hospital dataset that contains the total number of staff working at a hospital. The data is from the Centers for Medicare & Medicaid Services (CMS) and is collected from hospitals across the United States ,it can be used to compare hospital growth 

TRAUMA : is a deeply distressing or disturbing experience that can have lasting negative effects on a person's physical and mental health. It can be caused by a variety of events, including accidents, natural disasters, acts of violence, and abuse.


HELIPAD : is a landing area or platform for helicopters and powered lift aircraft. While helicopters and powered lift aircraft are able to operate on a variety of relatively flat surfaces, a fabricated helipad provides a clearly marked hard surface away from obstacles where such aircraft can land safely.

Helipads are common features at hospitals where they serve to facilitate medical evacuation or air ambulance transfers of patients to trauma centers or to accept patients from remote areas without local hospitals or facilities capable of providing the level of emergency medicine required.